# Palo Alto Lab 01 — Cloud Network Foundation

## 🎯 Objective
Build a segmented AWS VPC that simulates a traditional data center network with no internet access.

## 🧠 Key Concepts
- VPC as data center
- Subnet segmentation
- Routing fundamentals
- Default deny (Zero Trust foundation)

## 🏗️ Architecture
(Insert diagram in /architecture)

## 🔬 Implementation
- Created VPC (10.0.0.0/16)
- Built segmented subnets (Mgmt, Trust, Untrust)
- Configured route tables (no internet access)

## 🧪 Validation
- Internal connectivity works
- Internet access fails (expected)

## 📸 Evidence
See /evidence folder

## 📚 Lessons Learned
See /notes/lessons-learned.md
