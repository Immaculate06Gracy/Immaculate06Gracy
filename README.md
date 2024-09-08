from pandas import read_csv
from matplotib import pyplot
series=read_csv(r'C:\Users\Immaculate\Downloads\shampoo.csv')

print(series.head())
series.plot()
pyplot.show()![1000036971](https://github.com/user-attachments/assets/c46e14cc-faf2-4886-a2af-154f769d9c4c)

series.plot(style='_.')
pyplot.show()
![1000036972](https://github.com/user-attachments/assets/4186a8e8-b929-429b-b23f-18c829223077)


series.hist()
pyplot.show()
![1000036973](https://github.com/user-attachments/assets/6df6b0eb-9901-4fc6-bf65-6784f8d792cb)



series.plot(kind='kde')
pyplot.show()
![1000036974](https://github.com/user-attachments/assets/52980368-cb91-4256-8076-62b01e110990)
