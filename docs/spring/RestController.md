#1. Controller, RestController的共同点

     都是用来表示Spring某个类的是否可以接收HTTP请求
     
#2.  Controller, RestController的不同点

     @Controller标识一个Spring类是Spring MVC controller处理器

     @RestController：  a convenience annotation that does nothing more than adding the@Controller and @ResponseBody annotations。  @RestController是@Controller和@ResponseBody的结合体，两个标注合并起来的作用。
