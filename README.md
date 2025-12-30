# Web Traffic & Click Analytics (Linkfre Project)

This project performs basic **web traffic and user behavior analysis** using Python and Pandas. It processes event-level website logs to compute pageviews, click-through rates (CTR), geographic distribution of users, and link-level performance metrics.

## Features

- Load and analyze web traffic data from a CSV file
- Calculate total pageviews and daily pageview trends
- Analyze different event types (pageviews, clicks, etc.)
- Identify country-wise distribution of pageviews
- Compute overall click-through rate (CTR)
- Calculate click rate for individual links

## Dataset Structure

The project expects a CSV file (`traffic.csv`) with the following columns:

- `event` – Type of user event (e.g., `pageview`, `click`)
- `timestamp` – Date and time of the event
- `country` – User country
- `link` – Page or link identifier

## Technologies Used

- Python
- Pandas

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/linkfre-project.git
