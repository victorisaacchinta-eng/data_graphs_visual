# data_graphs_visual

A small Streamlit dashboard for looking at a CSV file. Upload a CSV from the sidebar and it shows a preview of the first rows, the row and column counts, the number of missing values and duplicate rows, and then whichever chart you pick.

Charts: histogram, box plot, scatter plot (with optional colour by a category column), line chart, bar chart (sum, mean or count per category), pie chart, violin plot, area chart, correlation heatmap and pair plot. Most are Plotly; the heatmap and pair plot use seaborn and need at least two numeric columns.

## Running it

The whole app is in the file `complete code`. Streamlit only runs `.py` files, so copy it to one first:

```bash
git clone https://github.com/victorisaacchinta-eng/data_graphs_visual.git
cd data_graphs_visual
pip install streamlit pandas numpy plotly seaborn matplotlib
cp "complete code" app.py
streamlit run app.py
```
