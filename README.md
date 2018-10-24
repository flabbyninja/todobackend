# Todobackend AWS Application

This repository provides a sample application based upon the [Todo-backend project](https://www.todobackend.com) from Docker in AWS

## Deploy ECS cloudformation of todoapp

aws cloudformation deploy --template-file stack.yml --stack-name todobackend --parameter-overrides $(cat dev.cfg) --capabilities CAPABILITY_NAMED_IAM 