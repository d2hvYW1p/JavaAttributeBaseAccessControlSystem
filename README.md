# Java Attribute Based Access Control System


The goal of this project is to design and implement an Access Control (ABAC) system that is able to offer effective protection against unauthorized access to applications and data stored in inherently insecure environments such as the cloud, by taking into account appropriate contextual attributes that characterize when a request is made.

This project is focused on one of the Cloud main challenges which is to provide a robust authorization mechanism. An attribute based access control system is proposed by presenting the idea of context-aware policies so as to establish a new efficient advanced model that can provide a more flexible and secure way of accessing data and services.  Ubiquitous access is for a fact  one of the biggest insecurity that cloud technologies have to deal with. This project will try to alleviate this insecurity by implementing the proposed access control system. It will manage resource access in a dynamic, context-aware, and policy-based manner, enabling for the establishment of an access control approach that contain specified qualities from a variety of different information sources in order to determine an authorization and ensure efficient regulatory compliance.

The software is composed of various technologies as java spring boot which is the cornerstone for creating restfull web services. The user interface is used for feeding the api endpoints with attributes so as to create XACML policies, XACML policy-sets and XACML Requests. The front end was mainly done with HTML,CSS and JavaScript(JQUERY). Furthermore it implements the eXtensible Access Control Markup Language as a standard that defines both a policy language and an access control decision request/response language. Through the Balana framework and WSO2 identity server libraries, we can dynamically build XACML Policies, Policy-Sets and evaluate Requests according to present Policies or Policy-Sets.
