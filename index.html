class Item:
    def __init__(self, name, price):
        self.name = name
        self.price = price

class CashRegisterPOS:
    def __init__(self):
        self.items = []
        self.order = []
        self.total = 0.0
        self.create_items()

    def create_items(self):
        # List of items available for purchase (32 items)
        self.items = [
            Item("Item 1", 5.00),
            Item("Item 2", 7.50),
            Item("Item 3", 10.00),
            Item("Item 4", 15.00),
            Item("Item 5", 20.00),
            Item("Item 6", 2.50),
            Item("Item 7", 8.00),
            Item("Item 8", 12.00),
            Item("Item 9", 3.75),
            Item("Item 10", 9.99),
            Item("Item 11", 14.50),
            Item("Item 12", 4.00),
            Item("Item 13", 6.75),
            Item("Item 14", 11.25),
            Item("Item 15", 5.50),
            Item("Item 16", 7.00),
            Item("Item 17", 13.25),
            Item("Item 18", 16.75),
            Item("Item 19", 18.00),
            Item("Item 20", 9.00),
            Item("Item 21", 3.00),
            Item("Item 22", 4.75),
            Item("Item 23", 6.25),
            Item("Item 24", 8.50),
            Item("Item 25", 10.75),
            Item("Item 26", 11.99),
            Item("Item 27", 14.00),
            Item("Item 28", 2.99),
            Item("Item 29", 5.99),
            Item("Item 30", 6.50),
            Item("Item 31", 12.50),
            Item("Item 32", 7.25)
        ]

    def display_items(self):
        print("\nAvailable Items for Sale:")
        for i, item in enumerate(self.items, 1):
            print(f"{i}. {item.name} - ${item.price:.2f}")

    def select_items(self):
        while True:
            self.display_items()
            try:
                item_num = int(input("\nEnter item number (1-32) to add to order, or 0 to finish: "))
                if item_num == 0:
                    break
                elif 1 <= item_num <= 32:
                    quantity = int(input(f"How many of {self.items[item_num-1].name} would you like to purchase? "))
                    self.order.append((self.items[item_num-1], quantity))
                else:
                    print("Invalid item number. Please try again.")
            except ValueError:
                print("Invalid input. Please enter a valid number.")

    def calculate_total(self):
        self.total = sum(item.price * quantity for item, quantity in self.order)
        print(f"\nTotal Order Amount: ${self.total:.2f}")

    def display_order(self):
        print("\nOrder Summary:")
        for item, quantity in self.order:
            print(f"{item.name} x{quantity} - ${item.price * quantity:.2f}")
        self.calculate_total()

    def copy_order(self):
        order_details = "\nOrder Summary:\n"
        for item, quantity in self.order:
            order_details += f"{item.name} x{quantity} - ${item.price * quantity:.2f}\n"
        order_details += f"\nTotal: ${self.total:.2f}\n"
        return order_details

def main():
    pos_system = CashRegisterPOS()
    print("Welcome to the Cash Register POS System")

    while True:
        pos_system.select_items()
        pos_system.display_order()
        
        action = input("\nWould you like to process another order? (y/n): ").lower()
        if action == 'n':
            break
        else:
            pos_system.order.clear()
            pos_system.total = 0.0

    order_copy = pos_system.copy_order()
    print("\nOrder Copy:")
    print(order_copy)

    # Optionally, you can write the order copy to a file
    with open("order_copy.txt", "w") as f:
        f.write(order_copy)
        print("\nOrder copy has been saved to 'order_copy.txt'.")

if __name__ == "__main__":
    main()
