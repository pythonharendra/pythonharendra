Prerequisites:

Python 3.7 or above installed on your machine.
Clone the Repository:

bash
Copy code
git clone https://github.com/your-repo/order-management-system.git
cd order-management-system
Run the Code: Ensure Python is installed and run the script directly:

bash
Copy code
python order_management.py


'''
create product :- 

seasonal_product = SeasonalProduct("Winter Coat", base_price=200, seasonal_discount_percentage=20)
bulk_product = BulkProduct("Notebook", base_price=5, bulk_discount_threshold=10, bulk_discount_percentage=15)


create discount:-

percentage_discount = PercentageDiscount(
    name="Holiday Discount",
    description="10% off during holidays",
    start_date=date(2024, 11, 1),
    end_date=date(2024, 12, 31),
    percentage=10
)

fixed_discount = FixedAmountDiscount(
    name="Clearance Sale",
    description="Flat $50 off",
    start_date=date(2024, 10, 1),
    end_date=date(2024, 10, 31),
    fixed_amount=50
)



