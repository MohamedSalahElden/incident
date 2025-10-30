---
hide:
  - navigation
  - toc
---

# Incidents of today


<div class="grid cards" markdown>

-   ![alt text](image.png)
    :material-security:{ .lg .middle } __Nihon Kohden CNS-6201 Central Monitor Vulnerability__

    ---

    A vulnerability in the Nihon Kohden CNS-6201 central monitoring system allows a remote attacker to send specially crafted UDP packets that cause the system to crash, resulting in a loss of monitoring capability. The flaw exists due to a NULL pointer dereference when processing malformed network data.

    **CVE-2025-59668** | **Impact:** Critical availability loss, patient safety risk

    [:octicons-arrow-right-24: View Full Details](nihon-kohden-cns-6201.md)

-   ![alt text](image-1.png)
    :material-lock-open:{ .lg .middle } __ASKI Energy ALS-Mini-S8 and ALS-Mini-S4 Vulnerability__

    ---

    A critical security vulnerability in the embedded web server of ASKI Energy ALS-Mini-S4 and ALS-Mini-S8 IP controllers allows remote attackers to access and modify configuration parameters without authentication. The flaw provides full administrative control over affected devices, compromising their operational integrity.

    **CVE-2025-9574** | **Impact:** Full device compromise, operational disruption

    [:octicons-arrow-right-24: View Full Details](aski-energy-als-mini.md)

-   ![alt text](image-2.png)

    :material-file-alert:{ .lg .middle } __Delta Electronics ASDA-Soft Vulnerability__

    ---

    Opening a specially crafted ASDA-Soft project file can trigger a stack-based buffer overflow, allowing data to be written outside the intended stack buffer. The issue exists in ASDA-Soft versions 7.0.2.0 and prior.

    **CVE-2025-62579** | **Impact:** Code execution, configuration compromise

    [:octicons-arrow-right-24: View Full Details](delta-electronics-asda-soft.md)

</div>