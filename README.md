Стефан Марковски 203180

2. Control flow graph

![](ControlFlowGraph.jpg)


4. Тест случаи според критериумот Every statement

1)list = null , vrakja : nisto(exception) , nodes: 1, 2, 19

2)list = {"0","#","0"} , vrakja : nisto(exception) , nodes: 1, 3, 4, 19

3)list = {"0","#","0","#","0","#","0","#","#"} , vrakja : {"2","#","2","#","4","#","2","#","#"} , nodes: 1, 3, 5, 6.1, 6.2, 6.3, 7, 8, 9, 10, 11, 12, 13, 14, 15, 16, 17, 18, 19


5. Тест случаи според критериумот Every Branch

1)list = null , vrakja : nisto(exception) , branches: 1-2, 2-19

2)list = {"0","#","0"} , vrakja : nisto(exception) , brances: 1-3, 3-4, 4-19

3)list = {"0","0","0","#","0","#","0","#","#"} , vrakja : {"1","0","1","#","3","#","2","#","#"} ,  branches: site osven 1-2, 3-4, 2-19, 4-19