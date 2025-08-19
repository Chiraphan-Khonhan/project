#!/usr/bin/env python3
import rospy

print("Hello world")

user_name = input("username: ")
pass_word = input("Password: ")

if user_name == 'admin':
    print('user correct')
    if pass_word == '1234':
        print('password correct')
    else:
        print('password incorrect')
else:
    print('user incorrect')
