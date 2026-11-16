# Newall machine monitoring: visual setup guide

An illustrated, step by step guide for connecting the shop-floor machines at Newall Engineering Works to the portal dashboard.

Open `index.html` in any browser. Tick boxes save on the device you use.

## Steps covered

1. Overview: machines, edge collector PC, cloud portal
2. Machine survey
3. Machine network cabinet (isolated 192.168.50.0/24)
4. Type A: newer FANUC CNCs over FOCAS (Ethernet)
5. Type B: older CNCs with a sensor node
6. Type C: manual machines with a sensor node
7. Edge collector PC (Ubuntu Server, Docker)
8. Cloud dashboard data flow
9. Shop-floor tablet view
10. Pilot plan (M/C 18, Puma 4100L, PV 9300)

Monitoring is read only. The machine network stays separate from the office network, and the collector only makes outbound connections.
