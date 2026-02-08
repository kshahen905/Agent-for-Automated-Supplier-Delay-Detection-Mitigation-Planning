## Project: AI Agent for Supplier Delay Detection & Mitigation (Supply Chain)

---

## 1. Problem Statement

Modern supply chain operations rely heavily on manual tracking of supplier deliveries using
spreadsheets, emails, and ERP dashboards. Delivery delays are often detected late, resulting in
production stoppages, inventory shortages, and financial losses.

This project addresses the bottleneck of **late detection and slow reaction to supplier delays**
by designing an **agentic AI system** that continuously monitors purchase orders, detects delivery
risks early, reasons using contractual Service Level Agreements (SLAs), and executes mitigation
actions automatically.

This problem cannot be solved with a single LLM prompt because it requires:
- Multi-source data perception
- Conditional, rule-based reasoning
- Stateful, multi-step decision flows
- External action execution

---

## 2. Industry Vertical

**Supply Chain & Operations**

---

## 3. User Personas

### Primary User: Procurement Manager
- Oversees supplier performance
- Responsible for on-time delivery of materials
- Needs early warnings and actionable insights

### Secondary User: Supply Chain Analyst
- Monitors logistics and shipment performance
- Reviews incidents and delay trends

---

## 4. Goals & Objectives

- Detect supplier delivery delays before deadlines are missed
- Automatically classify delay severity
- Enforce SLA-based escalation rules
- Reduce manual monitoring effort
- Improve reaction time to supply chain disruptions

---

## 5. Success Metrics

- Reduction in delay detection time (manual vs automated)
- Number of delays detected before deadline
- Accuracy of delay severity classification
- Reduction in manual intervention
- Number of successful automated alerts/escalations

---

## 6. Scope

### In Scope
- Monitoring purchase orders
- Shipment delay detection
- SLA-based reasoning
- Automated alerts and logging
- Mock data simulation

### Out of Scope
- Real ERP system integration
- Financial penalty execution
- Supplier negotiation automation

---

## 7. Constraints & Assumptions

- Uses mock data (CSV, PDFs, mock APIs)
- System designed for simulation, not production deployment
- LangGraph used for orchestration and state management

---

## 8. Risks

- Incorrect SLA extraction from documents
- Complex multi-agent coordination
- State inconsistency across agent nodes

---

## 9. Tools & Technologies

- Python
- LangGraph
- LangChain (document loading)
- CSV / PDF mock data
- Rule-based decision logic
