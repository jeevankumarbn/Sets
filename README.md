my_fav = {"mango","apple","grapes","kiwi"}
frie_fav = {"strawberry","kiwi","blueberry","dragon fruit"}

print(my_fav | frie_fav)  #union
print(my_fav & frie_fav)  #intersection
print(my_fav - frie_fav)  #difference

my_fav.add("banana")
print(my_fav)

my_fav.remove("apple")
my_fav.discard("strawberry")
print(my_fav)
