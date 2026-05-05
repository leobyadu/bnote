---
date: 2026-05-04
slug: aws-identity-access-management
---

# AWS Identity & Access Management (IAM)

IAM là trung tâm điều khiển an ninh của AWS. Nó cho phép quản lý ai có quyền truy cập (xác thực) và họ có quyền làm gì (phân quyền) đối với các tài nguyên trên AWS.

## Root User

Đây là "siêu tài khoản" được tạo ra ngay khi đăng ký tài khoản AWS bằng địa chỉ email.

Quyền hạn: Có toàn quyền tuyệt đối trên mọi dịch vụ và cả thông tin thanh toán (billing). Không thể bị giới hạn bởi bất kỳ Policy nào.

Khuyến nghị bảo mật: Chỉ nên dùng Root User để tạo IAM User đầu tiên, sau đó "khóa" nó lại. Luôn luôn phải bật MFA (Xác thực đa lớp) cho tài khoản này.

## IAM User

## IAM Policy

## Inline Policy vs Custom Policy

## IAM Group

## Multi IAM Group

## DENY effect

## IAM Role 

## Restricted User in role Trust Relationship

## Configure multiple user in Role Trust Relationship

## Principle vs Identity

## IAM Permssion Validation Order

## Permission Boundary

## IAM Components Relationship

## Configure AWS CLI

## Enabling Billing info for IAM User and Role

## Multi-Section on AWS Management Console 


