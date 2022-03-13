# Time_Series_Mercado
 An application that predicts search traffic using time series analysis.

---

## Technologies

This project uses Jupyter Lab in addition to the following libraries and add ons:

* [holoviews](https://holoviews.org/Reference_Manual/index.html) for visualization.

* [pandas](https://pandas.pydata.org/docs/) for working with dataframes.

* [matplotlib](https://docs.python.org/3/library/pathlib.html) for the data visualization.

* [hvplot](https://hvplot.holoviz.org/) for the data visualization.

* [fbprophet](https://facebook.github.io/prophet/docs/quick_start.html) for the time series forecasting.

* [datetime](https://docs.python.org/3/library/datetime.html) for working with timed data.

* [numpy](https://numpy.org/doc/) for various numerical functions.

---

## Installation Guide

Upload the notebook to Google Collab and run all of the cells, all of the dependencies will be installed there.

---

## Usage

The App imports all of the dependencies and asks you to upload the csv in resources:

![data_upload](https://user-images.githubusercontent.com/96391748/158049592-540a3870-8a57-4271-853d-275c57032176.PNG)

A portion of the data is sliced out then displayed:

![sliced_data](https://user-images.githubusercontent.com/96391748/158049613-c053b8ca-ff46-42b0-8c55-e67bc141902d.PNG)

The data is then mined for trends which are visualized:

![trends](https://user-images.githubusercontent.com/96391748/158049647-674c8107-c36d-4756-a450-93f09bca3d73.PNG)

The stock price data is then uploaded and also visualized:

![new_upload](https://user-images.githubusercontent.com/96391748/158049684-3a60affc-7504-4d11-8b73-53f560175cf7.PNG)

Finally, the data is forecasted into the future with each component visualized:

![forecasted_data](https://user-images.githubusercontent.com/96391748/158049697-b556bffb-c0ec-46a2-adaa-cd63c270f1f4.PNG)

---

## Contributors

* Nicklaus Danialy nickdanialy@gmail.com 

---

## License

Copyright (c) [2021] [Nicklaus Danialy]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
