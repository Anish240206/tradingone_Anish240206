# TradingOne

A comprehensive, web-based trading dashboard application designed with a primary focus on delivering a seamless, responsive, and visually engaging user experience. It provides real-time market data, cryptocurrency tracking, curated news feeds, and secure user authentication.

## Frontend Experience & User Interface

The core of TradingOne lies in its rich and engaging frontend architecture. 

* **Interactive Landing Page:** A modern, polished user interface featuring sleek hover effects, smooth transitions (like dynamic button coloring and underline interactions), and modular components to effortlessly direct users to key areas like login and market exploration.
* **Dynamic Market Tracking:** A structured, easy-to-read financial market grid that displays critical company metrics, including company name, real-time stock value, price fluctuations, and overall market cap.
* **Comprehensive Crypto Square:** A tailored cryptocurrency dashboard providing an in-depth view of the crypto market, tracking coin name, current value, percentage change, market cap, 24h volume, and circulating supply.
* **Curated News Feed:** An intelligent news aggregator presenting relevant market updates, carefully grouped and sortable by specific ranges—such as financial topics, diverse news sources, and publication dates.
* **Real-Time Data Integration:** Connects seamlessly with external APIs to populate the UI with accurate, live stock and cryptocurrency data streams, ensuring the dashboard actively represents the current state of the market.
* **Polished Footer Section:** A cleanly designed end-of-landing section housing project credits, essential navigation links, and necessary trademark information.

## Backend & Authentication

While prioritizing a premium frontend experience, TradingOne is additionally backed by a robust and secure server environment:

* **Express.js Server Engine:** Handles all backend routing and efficiently serves the frontend static assets.
* **Secure Local Database:** Incorporates SQLite for reliable, persistent user data storage.
* **Comprehensive Registration & Login System:** 
  * Standard Email & Password authentication with secure hash generated via `crypto`.
  * **JWT (JSON Web Token)** based session management for securing application endpoints.
* **Google OAuth Integration:** Offers seamless Single Sign-On (SSO) using the official `google-auth-library`, allowing users to register or log in instantly with their Google accounts.
* **Protected Member Routes:** Features dedicated secure environments, such as a protected terminal interface (`terminal.html`), accessible strictly upon successful JWT authentication.

## Tech Stack Overview

* **Frontend:** HTML, CSS, Vanilla JavaScript
* **Backend:** Node.js, Express.js
* **Database:** SQLite3
* **Security & Auth:** JWT, Google OAuth Library, pbkdf2 hashing (Crypto)

## Contributors

1. Ashutosh Gupta (24BCE2983)
2. Priyank Garg (24BCT0142)
3. Anish Agarwal (24BCT0234)
