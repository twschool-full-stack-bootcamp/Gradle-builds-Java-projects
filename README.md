# Gradle构建Java项目

## 练习内容
1.用Gradle命令行构建Java项目
2.用Gradle编译Java项目
3.用Gradle运行自动化测试
4.给Gradle添加idea插件，并生成Intellj Idea的项目文件
5.用Gradle运行程序输出“This is a Gradle Project”到命令行
6.添加Mockito依赖，并在测试方法中简单使用Mockito,使测试通过
```
    @Test
    public void testMockClass() throws Exception {
        // you can mock concrete classes, not only interfaces
        LinkedList mockedList = mock(LinkedList.class);

        // stubbing appears before the actual execution
        String value = "first";
        when(mockedList.get(0)).thenReturn(value);

        assertEquals(mockedList.get(0), value);

    }
```
