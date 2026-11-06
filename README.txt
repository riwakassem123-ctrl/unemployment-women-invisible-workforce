THE INVISIBLE WORKFORCE — STREAMLIT PROJECT

Project files:
- app.py: Streamlit dashboard
- data/Labour-force-FULFS-2022.xlsx: 2022 Labour Force survey workbook
- data/unemployment rate women.xlsx: historical World Bank/ILO unemployment estimates

Run instructions:
1. Extract the ZIP file.
2. Open a terminal in the extracted project folder.
3. Install the dependencies: pip install -r requirements.txt
4. Start the dashboard: streamlit run app.py

Keep the data folder beside app.py. The dashboard searches the project folder
and its data subfolder for the two Excel workbooks.
