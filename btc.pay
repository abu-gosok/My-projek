import requests

def get_btc_price():
    url = "https://api.coindesk.com/v1/bpi/currentprice/BTC.json"
    response = requests.get(url).json()
    price = response["bpi"]["USD"]["rate"]
    print(f"Harga Bitcoin saat ini: ${price}")

if __name__ == "__main__":
    get_btc_price()
