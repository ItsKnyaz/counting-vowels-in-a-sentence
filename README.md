# counting-vowels-in-a-sentence
The code counts the number of vowels in the sentence.
#подсчёт гласных в предложении
while True:
    text = input("Введите текст: ")
    vowels = "аеёиоуыэюя"
    count = 0
    for char in text.lower( ):
        if char in vowels:
            count += 1
    print(f"Гласных: {count}")
    input(f"\nНажмите Enter чтобы продолжить...")