import numpy as np
import pandas as pd
import streamlit as st
import altair as alt

st.header("st.write")
"""这是一个练习"""
# Example1
st.markdown('Hello , *world!* :sunglasses:')
st.write('Hello, *World!* :angry:')
# Example2
st.write(1234)
st.text(1234)
st.markdown(123)
st.subheader(3456)
st.caption(2468)
st.latex(135)
st.code("import streamlit as st")

# Example3
df = pd.DataFrame({'first column':[1,2,3,4],'second column':[10,20,30,40]})
st.write(df)

# Example4
st.write('Below is a DataFrame:', df, 'Above is a dataframe.')

# Example5

df2 = pd.DataFrame(np.random.randn(200, 3),columns=['a','b','c'])

c = alt.Chart(df2).mark_circle().encode(x='a', y='b', size='c', color='c', tooltip=['a', 'b', 'c'])
st.write(c)
