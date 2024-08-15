# bassebal
# Sample list of items (assuming they have attributes, such as type)
items = [
    {'type': 'baseball cap', 'color': 'blue'},
    {'type': 'socks', 'color': 'white'},
    {'type': 'baseball cap', 'color': 'red'},
    {'type': 't-shirt', 'color': 'green'},
    {'type': 'baseball cap', 'color': 'blue'}
]

# Count the number of baseball caps
num_baseball_caps = sum(1 for item in items if item['type'] == 'baseball cap')

print(f"Number of baseball caps: {num_baseball_caps}")
num_baseball_caps 
