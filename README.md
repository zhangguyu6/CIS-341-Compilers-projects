# upenn CIS 341 Compilers projects
宾夕法尼亚大学 cis314 编译器项目 主要以Ocaml完成
## project1
熟悉Ocaml语言，并用ocaml实现一个计算器
```
exp :=
  | Var of string         (* a string representing an object-language variable *)
  | Const of int32        (* a constant int32 value -- use the 'l' suffix *)
  | Add of exp * exp      (* sum of two expressions *)
  | Mult of exp * exp     (* product of two expressions *)
  | Neg of exp  
```