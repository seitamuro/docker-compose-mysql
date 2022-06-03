# 概要

docker-composeを利用して､MySQLのコンテナを作成する｡

# ディレクトリツリー

.
└── docker-mysql
    ├── docker-compose.yml
    └── mysql
        ├── DB
        │   └── world.sql
        ├── Dockerfile
        └── my.cnf

# つまづいたこと

my.cnfのcharacterをタイポしてコンテナがうまく起動しなかった｡
