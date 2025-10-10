# Test Summary Report

**Project:** Сітка Захід — B2B/B2C eCommerce Platform  
**Version:** 1.0  
**Date:** 10 March 2024  
**Author:** Hanna Spivachuk  

---

## Overview
Custom e-commerce platform for industrial metal products.  
Goal: validate purchase flow, admin management, and UI responsiveness.

---

## Scope
**Included:**  
- Product catalog and product details  
- Login and registration  
- Cart and checkout  
- Admin order management  
- Responsive layout (desktop/mobile)

**Excluded:**  
- Performance testing  
- Payment gateway API

---

## Test Approach
- Manual functional, UI/UX, and regression testing  
- Test design based on checklists and test cases  
- Defect tracking in Jira  
- Environments: Windows 11, Android, iOS  
- Browsers: Chrome, Firefox, Safari  

---

## Test Results
| Category      | Total  | Passed | Failed | Blocked |
|---------------|:------:|:------:|:------:|:-------:|
| Functional    | 84     | 79     | 4      | 1       |
| UI/UX         | 26     | 24     | 2      | 0       |
| Regression    | 30     | 30     | 0      | 0       |

**Overall pass rate:** 95%  
**Testing period:** 20 Feb – 10 Mar 2024  

---

## Defect Summary
| ID      | Severity | Status | Description |
|---------|----------|--------|-------------|
| BUG-001 | Critical | Fixed  | Incorrect price calculation for discounted items |
| BUG-004 | Medium   | Fixed  | Misaligned header on mobile |
| BUG-007 | Low      | Open   | Tooltip not visible on info icon |

This summary includes major and representative defects identified during the testing cycle.

---

## Conclusion
Testing objectives were **successfully met**.  
The product is **ready for UAT**, pending fix of low-severity defects.

**Recommendations:**
- Re-test after deployment  
- Add performance testing in future  
- Create automated smoke suite for checkout flow

---

**Document status:** ✅ Completed  
