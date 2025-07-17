# EY Rill Dashboards

A collection of Rill dashboards and metrics for general ledger data analysis.

## Example Visuals

Below are some example visuals from the dashboards:

<img width="1174" alt="Screenshot 2025-07-09 at 9 02 59 AM" src="https://github.com/user-attachments/assets/04dfa806-5a77-471b-8a6d-a518f191eec1" />
<p align="center"><i>General Ledger Overview</i></p>

<img width="1511" alt="Screenshot 2025-07-09 at 9 03 21 AM" src="https://github.com/user-attachments/assets/3f5853f5-dfe0-4612-946a-43b551fc2424" />
<p align="center"><i>Detailed Metrics Explore</i></p>

## Features

- Pre-built dashboards for general ledger data
- Fast, interactive exploration with Rill
- Easy to extend with new metrics and sources

## Getting Started

1. **Clone the repository:**
   ```sh
   git clone https://github.com/your-org/ey_rill.git
   cd ey_rill
   ```

2. **Install Rill (if not already installed):**
   ```sh
   curl -s https://cdn.rilldata.com/install.sh | bash
   ```

3. **Start Rill:**
   ```sh
   rill start
   ```

4. **Load the data into Rill:**
   - You can use ClickHouse or DuckDB as your backend. DuckDB is easier to set up for local testing.
   - Example data files (fake data) used for this project:
     
     [Download part of the sample data from this S3 bucket](https://agreeable-data-public.s3.amazonaws.com/sampleeydata/gl_data_1b_part000.parquet)

## Project Structure

- `connectors/` – Data source connector configs
- `dashboards/` – Dashboard YAML definitions
- `metrics/` – Metric definitions
- `sources/` – Source data configs
- `rill.yaml` – Rill project configuration

