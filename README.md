FDPS-Nbody simulation code
  (last update in 2018.5.23)
====

## Discription
このプログラムは大規模並列計算向けの重力多体系のシミュレーションを[FDPS](https://github.com/FDPS/FDPS "FDPS-github")を用いて行うことができる。

### Simulation problem
    * Cold Collapse
    * Plummer sphere
    * M31 system and satellites

## Usage
Makefileのマクロ定義を変更することでシミュレーションの性質を変更できる。

### Defined macros in Makefile

## How to use
実行ファイル（galaxy.out）はrootディレクトリでmakeコマンドを実行して生成する。
プログラム実行にはrootディレクトリ下のshellファイルを実行するのも良い。
```
$ make
$ ./galaxy.out [Options] [Option value]
$ local.sh
```

## Licence
Miyagawa Ginjiro(Univ. Tsukuba student): email ginmiya@ccs.tsukuba.ac.jp
