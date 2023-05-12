# Mastering-Pointers-in-C-super-guide
 

# C pointers

Pointers are special variables which are used to store addresses rather than values.
 ## Syntax

1. **Declaration**
```C
    int* p;
    int *p;
    int * p; //We are declaring pointer p of type int.
    int* p1,p2; // p1 is pointer of type int , but p2 is anormal variable
```
2. **Assigning address to Pointers**

```C
int *pc,c;
c=5;
pc=&c; // Address of c is assigned to pc pointer
```
3. **Get values pointer by pointers**

```C
int *pc,c;
c=5;
pc=&c;
c =5;
printf("%d",c); //output : 5
printf("%d",*pc);//output : 5
```
```C
int *pc,c,,d;
c =5;
d = -15;
pc = &c ; printf("%d",*pc); //output : 5
pc = &d ; printf("%d",*pc); //output :-15
```
