#split the bill with your friends (empty answers won't work sorry)

bill_total = float(input("how much is the total bill?:\n"))
people_total = int(input("how many people are splitting?:\n"))
tip_percentage = float(input("what's your % for tipping?:"))
split_bill = bill_total * ((tip_percentage) / 100 + 1) / people_total
rounded_split_bill = "{:.2f}".format(split_bill)
print(rounded_split_bill)
