def calculate_gold_value(weight, rate):
    value = weight * rate
    return value

weight = float(input("Enter the weight of gold in grams: "))
rate = float(input("Enter the current gold rate per gram: "))

gold_value = calculate_gold_value(weight, rate)
print("The value of the gold is: $", gold_value)
