# lecture-test2
import streamlist as st 
import pandas as pd
import plotly.express as px
st.titile("Streamlit Demo")
st.subheader("by M.Y.")
gpa = pd.read_csv("http://logopt.com/data/SATGPA.csv",index_col=0)
st.write(gpa)
st.write(gpa.hist(bins=30);)
