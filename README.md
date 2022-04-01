<!-- HEADINGS -->

# My title
## My title h2
### my title h3
#### my title h4
##### my title h5
###### my title h6

<!-- ITALIC -->

this is an *italic* text 

<!-- STRONG -->
this is an **strong** text

<!-- STRIKETHROUGH -->
este es un ~~texto~~ tachado


<!-- UL -->
* apple
    * apple 2
        * aple 3
* orange
    * orange 2
* etc

1. apple
2. orange
3. etc

[facebook.com](https://www.facebook.com/)

[facebook.com](https://www.facebook.com/ "Custom Title")

<!--cita -->
> this is a quote

---
___

`console.log('hello world')`

<!-- bloque de codigo-->

```sql
create or replace procedure autor_libro( atitulo in varchar2)
as
    v_autor varchar2(20);
    begin
    select autor into v_autor from libros where titulo = atitulo; 
    select titulo, precio from libros  
    where autor = v_autor; 

end autor_libro;
 ```

 ``` python
 print("hello world")

 ```


  ``` html
<h1>Helloworld</h1>

 ```

 <!--tablas -->

 | Table            | Are               |   Cool   |
 | -----------------| :----------------:| --------:|
 | col 3 is         | right-aligned     |  $1600   |
 | col 2 is         | centered          |  $12     | 
 | zebra stripes         | are neat     |  $12     | 

 ![visual studio code logo](https://www.solucionex.com/sites/default/files/posts/imagen/vscode-800x450.png)

  ![visual studio code logo](vscode.png "vscode logo")


  <!-- github markdown-->
  * [x] task1
  * [] task2
  * [] task3
  * [x] task4