# stools
一个简单的小工具集，开发者可以根据需求自定义服务，然后可以通过接入层（web接入）进行访问到自定义的服务。

系统整理分为两部分，一部分是系统核心，提供核心的路由和执行流程。另一部分是外部服务，开发者自定义服务，通过接入层对外暴露。

核心主要提供默认基于Netty的Http接入。

为了便于开发者开发服务，核心提供了数据库访问工具，Redis访问工具以及其他的一些简单的工具类。

此小工具经历过超小并发量的生产验证。

## k-db
数据库工具类

## k-redis
redis工具类

## k-utils
一些常用的工具集

## k-core
提供了核心的接口，注解。封装核心方法

## k-config
配置中心

## k-access-layer
接入层，目前提供基于Netty的Http接入层，对外提供Web服务
