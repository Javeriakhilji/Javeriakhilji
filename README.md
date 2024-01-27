- 👋 Hi, I’m @Javeriakhilji
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
Javeriakhilji/Javeriakhilji is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->while True:
    optr = input("1. Add\n2. Substract\n3. Multiply\n4. Divide\n5. Exit\n")

if optr == "1":
    n1 = int(input("enter first value:"))
    n2 = int(input("enter second value:"))
    sum = n1 + n2
    print("the sum is:",sum)

elif optr == "2":
    n1 == input("enter first value:")
    n2 == input("enter second value:")
    diff == n1 - n2
    print("the diff is:",diff)

elif optr == "3":
    n1 = input("enter first value:")
    n2 = input("enter second value:")
    prod = n1 * n2
    print("the prod is:",prod)

elif optr == "4":
    n1 = input("enter first value:")
    n2 = input("enter secnd value:")
    div = n1 / n2
    print("the quotient is:",div)
elif optr == "5":
 break
else: print("enter correct optr!")

