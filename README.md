# CoinSpot Python 
-Work in progress- Python 3+

Currently designed for the Read Only CoinSpot API endpoint.


# Establish Connection:
coinSpotAPI = CoinSpot('enter API key here', 'enter API secret here')

# Return JSON object of all owning crypto's and values:
print(CoinSpotAPI.myBalances())
