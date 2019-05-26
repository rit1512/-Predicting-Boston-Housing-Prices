# -Predicting-Boston-Housing-Prices

Packages required

    Python 3.7.0
    Matplotlib
    Pandas
    Numpy
    scikit-learn







Output Sample
client_data = [[5, 17, 15], # Client 1

               [4, 32, 22], # Client 2

               [8, 3, 12],  # Client 3

               [4,17,12]]   #Client  4

​

​

for i, price in enumerate(reg.predict(client_data)):

    print("Predicted selling price for Client {}'s home: ${:,.2f}".format(i+1, price))
    
    Predicted selling price for Client 1's home: $411,096.00
Predicted selling price for Client 2's home: $219,961.54
Predicted selling price for Client 3's home: $955,500.00
Predicted selling price for Client 4's home: $321,562.50
    
    

                            
