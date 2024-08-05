# pandas-challenge-1
## External resources 
https://numpy.org/doc/stable/reference/generated/numpy.ndarray.tolist.html#numpy.ndarray.tolist
index.tolist()

AskBCS Learning
    Vijaya Reddy - Helped fix an issue with rounding of decimal places.
df['line_price'] = round((df['line_subtotal']+df['shipping_price'])* 1.0925,2)
    This line screwed up the rest of the decimal rounding for the project. We added the ,2 and it fixed it.
