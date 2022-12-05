# ntcode12-_NumPy_Amsterdam_AirBnB
Numpy and Numba Skills Refresh

This project was an opportunity for me to refresh my skills in Numpy and Numba. The project involved the use of a dataset of Airbnb listings in Amsterdam, which I cleaned and transformed using Numpy.

I used NumPy and Numba to improve the performance of a function that calculates the distance from an Airbnb listing to a specific location (the Johan Cruijff ArenA). 

To improve the performance of the distance calculation function, the first step was to vectorize the calculation using NumPy. This allowed for much faster calculations by taking advantage of NumPy's ability to operate on entire arrays at once, rather than looping through each element individually.

Next, the Numba package was used to further improve performance by compiling the vectorized calculation into machine code. This allowed the function to run even faster, making it suitable for use in larger datasets.

The streamlit app was then used to visualize the data, which included a histogram showing the distribution of prices and a map showing the locations of the Airbnb listings and the chosen location. This allowed for easy exploration of the data and provided valuable insights into the listings available.

Overall, this project was a great way to refresh and improve my skills with NumPy and Numba, and showed the power of these tools in improving the performance of data analysis functions.
