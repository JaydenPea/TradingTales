Here's an updated README for your repository:

---

# TradingTales

**TradingTales** is a comprehensive trading journal application designed to help traders track, analyze, and optimize their trading strategies. This app features a robust set of tools for graphing trading data, reviewing historical trades, uploading trade records, and exporting data.

## Tech Stack

- **Backend**: Supabase (PostgreSQL with TimescaleDB extension)
- **Frontend**: jQuery, JavaScript, Razor Pages
- **API**: Web API for seamless data interaction

## Features

- **Graphing**: Visualize trading metrics and trends with interactive graphs.
- **Historical Data**: Review and analyze past trades to identify patterns and improve strategies.
- **Trade Upload**: Easily upload trade records to the system for tracking and analysis.
- **Data Export**: Export trading data in various formats for external analysis and reporting.

## Getting Started

### Prerequisites

- [.NET SDK](https://dotnet.microsoft.com/download) for Web API development.
- [Supabase Account](https://supabase.io/) for backend services.
- [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) for frontend development.

### Setup

1. **Clone the Repository**

    ```bash
    git clone https://github.com/JaydenPea/TradingTales.git
    cd TradingTales
    ```

2. **Backend Configuration**

    - Configure your Supabase instance and set up the PostgreSQL database with TimescaleDB extension.
    - Update the API configuration to connect to your Supabase instance.

3. **Frontend Setup**

    - Navigate to the `frontend` directory.
    - Install dependencies:

      ```bash
      npm install
      ```

4. **Run the Application**

    - Start the Web API:

      ```bash
      dotnet run
      ```

    - Start the frontend application. This will typically involve running a local server to serve your Razor Pages.

5. **Access the Application**

    Open your browser and go to `http://localhost:5000` to access the application.

## Usage

- **Graphing**: Use the graphing tools on the dashboard to visualize trading metrics.
- **Historical Data**: Navigate to the historical data section to review past trades.
- **Upload Trades**: Use the trade upload form to add new trade records to your journal.
- **Export Data**: Go to the export section to download your trading data.

## Contributing

Feel free to submit pull requests or open issues to contribute to the project. Your feedback and contributions are welcome!

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

For any questions or feedback, please reach out to the project maintainer at [jaydenpea@example.com](mailto:jayden.pearce12@gmail.com).
