---
layout: post
title: Background rule
date: 2016-11-16
---

Backend - basically slacker . Therefore, it is not necessary to keep it in memory.
SO use this:

FastCGI for those who often runs the PHP,
Phusion Passenger for those who wrote on the "rails"
PostgresSQL as best DB. By the way it can do pipelining

Also start using Go - new language with efficient network IO and multi-tasking
And don`t forget to translate big slice of the business logic into database level:

When designing database applications, I use a very simple mantra:
You can do it with one SQL statement;
It can be done using a single SQL statement;
It can be done in PL / SQL, try to use a stored procedure in the language Java;
It can be done in Java, do it as an external procedure in the language C;
if it can not be implemented as external procedures in the C language, it is necessary to think seriously, why do it at all ...

My approach is to do everything in the database if possible.