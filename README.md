# Cleaning service
Cleaning company's simplified system design with api design and deploy plan.

# Table of Contents
- [Cleaning service](#cleaning-service)
- [Table of Contents](#table-of-contents)
- [Ubiquitous language](#ubiquitous-language)
- [User Story](#user-story)
- [Technical Requirements](#technical-requirements)
- [API Design](#api-design)
- [Architecture](#architecture)
  - [General](#general)
  - [Employee service](#employee-service)
  - [Order service](#order-service)
  - [Verification service](#verification-service)
  - [Pricing service](#pricing-service)
  - [Payment service](#payment-service)
  - [Customer service](#customer-service)
- [Deploy plan](#deploy-plan)


# Ubiquitous language
- Customer <- User
- Order <- Cleaning order
- Verification service <- component for verifying the order
- Squares <- The area of the building or premises
- Cleaning types <- types of cleaning depending on different rooms and complexity

# User Story

Cleaning company's user story created for subsequent conversion into technical requirements. 

2 Way for creating order.

Via phone calls:

1. Customer call to employee for order cleaning.
2. The customer asks for a price and describes the condition and area of the room or office that needs to be cleaned.
3. If customer agree with price then the customer provides his data like name, last name, email(optional), phone number if customer need to change phone number, date for cleaning if employee is available.
4. If the customer want to sign online contract (blank service) employee send contract to the customer via email and the customer sign contract.
5. On the day of cleaning, the customer must sign the contract and, after cleaning, make payment through the employee’s application or in cash.

Via website:

1. Customer open website, scroll to forms.
2. The customer calculates price using the types of cleaning and the area of the room or office to be cleaned.
3. Then the customer fill forms with name, last name, email, phone number, date for cleaning if employee is available and submit forms.
4.  Employee call to the customer for verification of order.
5.  If the customer want to sign online contract (blank service) employee send contract to the customer via email and the customer sign contract.
6.  On the day of cleaning, the customer must sign the contract and, after cleaning, make payment through the employee’s application or in cash.
   
# Technical Requirements

# API Design

# Architecture

## General

## Employee service

## Order service

## Verification service

## Pricing service

## Payment service

## Customer service

# Deploy plan
