---
layout: post
title: A Build System for .NET Core
---

## Introduction 

I love build scripting systems like Cake. 
- Consistent build experience on local dev machine as well as build server
- By virtue of the entire build being controlled by the script, there is hardly any dependency on the CI server. 
- A system like Cake which uses a C# DSL is easy to wrap your head around. 

## .NET Core

- Traditionally cake uses the Mono framework to orchestrate the build on Linux 
- I want a build system to have as few dependencies as possible.
- If you are working with docker already as part of your dev workflow, wouldn't it be nice if a docker container could be used as a build environment?!

Refer this: https://blogs.msdn.microsoft.com/stevelasker/2016/09/29/building-optimized-docker-images-with-asp-net-core/ and simplify steps. Augment with own experiences.