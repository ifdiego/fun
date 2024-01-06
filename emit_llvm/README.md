# emit_llvm

Experiments with LLVM IR.
Emit IR in different languages backed by LLVM itself.

#### Using clang
```
# assembly
clang linked_list.c -S
# llvm ir
clang linked_list.c -S -emit-llvm
```

#### Using rustc
```
rustc llist.rs --emit llvm-ir
```

#### LLVM tools
```
# execute the llvm ir
lli linked_list.c
# generate assembly
llc llist.ll
```
