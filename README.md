# Aggregation WebSocket Data Streaming and Visualization

## Description
This Jupyter Notebook demonstrates real-time data streaming and visualization using WebSocket technology. The notebook focuses on streaming aggregated trade data from the Binance API, processing the data, and visualizing volume comparison over time.

## Features
- **WebSocket Connection**: Establishes a WebSocket connection with the Binance API to stream aggregated trade data for the BTC/USDT trading pair.
- **Data Processing**: Processes the incoming aggregated trade data, including extracting event time, symbol, price, quantity, and buyer market maker information.
- **Real-Time Visualization**: Dynamically visualizes volume comparison between buyer market makers and non-market makers over time using Plotly.
- **Threading**: Utilizes threading to handle WebSocket connections, data processing, and visualization concurrently.

## Usage
1. Open the Jupyter Notebook environment.
2. Copy and paste the provided code into a new notebook cell.
3. Execute the cell to start the WebSocket connection and real-time visualization.
4. The notebook will display volume comparison plots as data streams in from the WebSocket.

## Dependencies
- Python 3.9.18
- Pandas: Data manipulation library.
- Plotly: Interactive visualization library.
- websocket-client: WebSocket client library.

## Note
- Ensure you have an active internet connection to establish the WebSocket connection with the Binance API.
- This notebook is for educational purposes and demonstrates real-time data streaming and visualization techniques.

## Contact
For any inquiries or support, please contact arman13m99@gmail.com
