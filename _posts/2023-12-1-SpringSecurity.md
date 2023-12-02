---
layout: post
title: "SpringSecurity系列"
date:   2023-12-2
tags: [开发]
comments: false
author: AuTtx
---

## 一、开篇
《Spring OAuth2 开发系列》是系列文章，详细介绍基于 Spring 生态（包括 Spring Cloud） OAuth2 的实战开发。本系列将由3～5篇文章组成：

（一）体系架构和开发概览：是系列文章的开篇，主要对 OAuth2 的体系架构和主要流程进行梳理剖析，并对当前 Spring OAuth2 开发做一个概括性、全局性介绍；
（二）OAuth2 密码模式开发实例
（三）OAuth2 客户端模式开发实例
（四）OAuth2 授权码模式开发实例
（五）OAuth2 微服务场景实例开发：以密码模式为例，介绍在微服务场景下使用 OAuth2 以及整合 JWT 的关键技术方法，主要围绕客户端、微服务网关、认证授权服务进行，不涉及微服务的其他模块等。
本系列第一篇主要聚焦 OAuth2 体系的概念介绍，其余各篇偏向于实战，主要实现 OAuth2 的三种授权模式：密码模式、客户端模式和授权码模式，包括展示授权服务器、资源服务器、客户端等几种角色的交互，以及 JWT 的整合。
注：每个实例目前仅会提供一个代码版本：基于旧的 Spring Security OAuth2 组件。基于新的 Spring Authorization Server 代码示例敬请期待...