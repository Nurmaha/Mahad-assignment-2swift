class Location: 91 St john st toronto 
    def __init__(self, x, y):
        self.x = x
        self.y = y

class Customer:
    def __init__(self, amy, amywill@yahoo.com , 416-500.2323, accepted_newsletter,toronto):
        self.name = name
        self.email = email
        self.phone_number = phone_number
        self.accepted_newsletter = accepted_newsletter
        self.location = location

def calculate_distance(loc1, loc2):
    # Assuming Euclidean distance for simplicity
    return ((loc1.x - loc2.x) ** 2 + (loc1.y - loc2.y) ** 2) ** 0.5

def print_emails_within_range(store_location, customers, store_range):
    for customer in customers:
        distance = calculate_distance(store_location, customer.location)
        if distance <= store_range:
            print(f"Name: {customer.name}, Email: {customer.email}")

# Example usage
store_range = 2.5
store_location1 = Location(1, 2)
store_location2 = Location(3, 4)

customers = [
    Customer("Jane Doe", "jdoe@gmail.com", "123-456-7890", True, Location(1.5, 2.5)),
    # Add more customers here...
]
class Location:
    def __init__(self, x, y):
        self.x = x
        self.y = y

class Customer:
    def __init__(self, name, email, phone_number, accepted_newsletter, location):
        self.name = name
        self.email = email
        self.phone_number = phone_number
        self.accepted_newsletter = accepted_newsletter
        self.location = location

def calculate_distance(loc1, loc2):
    # Assuming Euclidean distance for simplicity
    return ((loc1.x - loc2.x) ** 2 + (loc1.y - loc2.y) ** 2) ** 0.5

def print_emails_within_range(store_location, customers, store_range):
    for customer in customers:
        distance = calculate_distance(store_location, customer.location)
        if distance <= store_range:
            print(f"Name: {customer.name}, Email: {customer.email}")

# Example usage
store_range = 2.5
store_location1 = Location(1, 2)
store_location2 = Location(3, 4)

customers = [
    Customer("Jane Doe", "jdoe@gmail.com", "123-456-7890", True, Location(1.5, 2.5)),
    # Add more customers here...
]

print_emails_within_range(store_location1, customers, store_range)


print_emails_within_range(store_location1, customers, store_range)
