# 🇿🇦 B-BBEE Scorecard Simulator & Reality Check

> **Live Application**: [https://bongamanzini.github.io/bee-simulator-reality-check/](https://bongamanzini.github.io/bee-simulator-reality-check/)

An interactive socio-economic decision-support simulator modeling the South African Department of Trade, Industry and Competition (DTIC) Codes of Good Practice (Generic and QSE scorecards).

---

## 🎯 The Informatics & Social Impact Angle

- **The Problem**: A recurring political and social narrative claims that *"white business owners are banned from the economy or tenders."*
- **The Informatics Solution**: A transparent, mathematical decision-support system modeling the exact point allocations of the DTI Codes of Good Practice.
- **The Reality Check**: The simulator proves mathematically that **ownership represents only 25 out of 109 Generic points**. By investing in Skills Development (learnerships, bursaries), Enterprise & Supplier Development (ESD), and Socio-Economic Development (SED), a **100% white-owned company (0 ownership points) easily achieves Level 4 Compliance (100% Procurement Recognition)** without changing its equity structure.

---

## 📊 Scorecard Elements Modeled

1. **Ownership (25 pts)**: Voting rights, economic interest, and net value. Includes the 40% sub-minimum rule (10 pts).
2. **Management Control (19 pts)**: Board representation and executive management.
3. **Skills Development (25 pts)**: Training expenditure on designated staff and registered learnerships (Priority Element, 40% sub-minimum = 8 pts).
4. **Enterprise & Supplier Development (42 pts)**: Preferential procurement, supplier development contributions, and enterprise incubation (Priority Element, 40% sub-minimum = 16 pts).
5. **Socio-Economic Development (5 pts)**: Community health, education, and social development spend (1% NPAT).

### Priority Element Discounting Logic
Implements the official DTI rule: if a business misses the 40% sub-minimum on Ownership, its achieved qualification drops by **one full level** (e.g., from Level 3 to Level 4).

---

## 🚀 Key Features

- **Interactive Dynamic Sliders**: Real-time recalculation of points, levels, and procurement recognition factors.
- **Pre-Configured Scenarios**:
  - `100% White-Owned SME`: Demonstrates Level 4 compliance through human capital & supplier investments.
  - `100% Black-Owned Enterprise`: Full redress Level 1 status.
  - `JSE Generic Corporation`: Typical diversified corporate equity.
  - `Untransformed Entity`: Explains why failing to train staff results in non-compliance.
- **Commercial Tendering Assessment**: Summarizes real-world implications for RFP eligibility and mining charter compliance.

---

## 💻 Tech Stack

- **Frontend**: HTML5, Modern Vanilla JavaScript (ESNext)
- **Styling**: Tailwind CSS
- **Icons**: Lucide Icons
- **Deployment**: GitHub Pages (Continuous Deployment)

---

## 👨‍💻 Author

**Bonga Manzini**  
BSc Informatics – University of South Africa (UNISA)  
*Part of the South African Socio-Economic Informatics Portfolio*  
Portfolio: [https://bongamanzini.github.io/portfolio/](https://bongamanzini.github.io/portfolio/)
