# Point-to-Point-UDP-Traffic-Transmission-over-IEEE-802.11g
In this project we analyze the UDP traffic between an Access Point (AP - router) and a Station Point (STA - hosts). For the purposes of this project we have used the indoor testbest of the NITlab labs from the University of Thesally.

# Experiments
Since we have created the Access Point (AP) and successfully connected the Staion Point (STA) to it, begin executing the experiments by sending UDP traffic from the network's AP to its STA using the following parameters:
1. Transmission duration **30 seconds**, transmition rate **5 Mbps**.
2.  Transmission duration **30 seconds**, transmition rate **15 Mbps**.
3.   Transmission duration **30 seconds**, transmition rate **100 Mbps**.

The experiments are taking place using the **iperf** command. The initialization of the parameters is on the **hostapd.conf** file.

# Repository Structure

| Path | Contents |
| --- | --- |
| [`log_iperf_X_AP.txt`](log_iperf_5M_AP.txt)(log_iperf_15M_AP.txt) | Python backend with Flask routes, the MySQL connection, and SQL queries for the application features. |
| [`uni_app_database.sql`](uni_app_database.sql) | SQL dump containing the relational schema and project data. |
| [`hostap.conf`](hostap.conf) | Configuration file for the AP. |
| [`report.pdf`](report.pdf) | Project report detailing the methodology, experimental steps (including **iperf** commands), result analysis, and supporting screenshots. |
| [`1st Assignment.docx.pdf`](1st Assignment.docx.pdf) | Assignment PDF containg the original problem statement. |

# Academic Context
This project was developed during the spring semester of the 2024-2025 academic year for the subject of **Wireless Communications**, at the Department of Electrical and Computer Engineering, University of Thessaly. The operational protocol is  **IEEE 802.11g**. 
