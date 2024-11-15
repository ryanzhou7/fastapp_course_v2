# FastAPI course v2

## Introduction

This course will teach you

1. FastAPI
2. Best practices of FastAPI
3. Industry standard libraries for data persistence
4. Deployment

## Setup

This repo has been setup such that all "solutions" are available, but you still can freely make commits.

Before we go into how we're learning the material, we need to finish the repo setup.

We will first need to fork this repo.

You may be familiar with cloning repos, which downloads a repository from GitHub to your local machine. You can clone your own repositories, forks, or any public repository.

Forking is slightly different.

Forking creates a personal copy of someone else's repository on your GitHub account. It allows you to make changes without affecting the original repository and to contribute back via pull requests.

In this case we want to fork because you cannot commit code and push them unless you have write permissions to this repo.

Find and click the "Fork" button for this repo.

Clone this repo to your local.

Remember, this is your repo. You have all admin permissions.

One difference between this original repo and your fork is that your forked repo will not have the existing pull requests (PRs).

For the "solutions", you will find them in the form of PRs in this original repos like [this PR](https://github.com/ryanzhou7/fastapp_course_v2/pull/1/files)

It is encouraged that you commit code on your original repo as if you were the developer adding the feature.

## Methodology

Now we discuss the how of learning the curriculum above.

In general, we want to make small incremental steps. i.e. understanding all the existing material / code, then add the smallest chunk possible to learn, and repeat.

Though the smallest chunk possible would ideally be, well, small, sometimes that is not possible.
Hence, each lesson will have a rating to help manage expectations.

| Symbol | Difficulty |
| ------ | ---------- |
| 🙂     | Easy       |
| 🤨     | Medium     |
| 🤯     | Hard       |

In short,

1. We will use the [FastAPI-template](https://github.com/s3rius/FastAPI-template) tool to generate our project.
2. The FastAPI-template takes flags as input, we will start with flags that output the most simple FastAPI possible
3. We will understand all the code that has been outputted
4. We add another flag and re-generate the project so it has another feature and more code (for example, database access)
5. Repeat until we've arrived at a FastAPI codebase that is similiar to typical companies using FastAPI

The lessons are numbered ch1, ch2, etc... please proceed to the next chapter in the [chapters](/chapters) folder
