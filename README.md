import random
#randint()
print(random.randint(1,10))
#choice(list)
colors = ["green","red","blue"]
print(random.choice(colors))
#shuffle(list)
nums = [1,2,3,4,5]
random.shuffle(nums)
print(nums)
#random()
print(random.random())
fruits = ["apple","banana","grapes","pineapple"]
print(random.choice(fruits))
random.shuffle(fruits)
print(fruits)
