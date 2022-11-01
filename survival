import random
import sys
import time



biome = ['Лесу','Пустыне','Снежной Долине','Болоте']

food = ['рыба','мясо','ягоды']

forest_predators = ['медведи','волки','койоты','лисы']

desert_predators = ['змеи','грифоны','койоты','рыси']

snowy_predators = ['волки','медведи','тигры']

swamp_predators = ['крокодилы','комары']

forest_shelter = ['пещере','дерево','хижине']

desert_shelter = ['хижине','маленькой пещере']

snow_shelter = ['домике','пещере']

swamp_shelter = ['пещере','дерево','хижине']
how_long = ['1 день', '2 дня','3 дня','4 дня','5 дней','6 дней','1 неделю','2 недели','3 недели', '1 месяц']

biome_choice = random.choice(biome)
food_choice = random.choice(food)
how_long_choice = random.choice(how_long)

if biome_choice == 'Лесу':
    predator_choice = random.choice(forest_predators)
    shelter_choice = random.choice(forest_shelter)
if biome_choice == 'Пустыне':
    predator_choice = random.choice(desert_predators)
    shelter_choice = random.choice(desert_shelter)
if biome_choice == 'Снежной Долине':
    predator_choice = random.choice(snowy_predators)
    shelter_choice = random.choice(snow_shelter)
if biome_choice == 'Болоте':
    predator_choice = random.choice(swamp_predators)
    shelter_choice = random.choice(swamp_shelter)
def live():
    live_choice = random.randint(1,4)
    if live_choice == 4:
        print('Вы не выжили, Причина смерти: ' + food_choice + ' оказалось ядовитым')
    if live_choice == 3:
        print('Вы не выжили, Причина смерти: ' + predator_choice + ' напали на тебя!')
    if live_choice == 2:
        print('Вы не выжили, Причина смерти: Грязная вода')
    if live_choice == 1:
       print('Вы выжили!' + food_choice + ' были хорошим источником пищи, ' + predator_choice + ' оставили тебя в покое')

def main():
   print('Эта игра написана Прониным Игорем')
   name = input()
   print(f'Добро пожаловать в симулятор выживания {name}!')
   print('')
   print('Вы потерялись в ' + biome_choice)
   print('Вы живете в ' + shelter_choice)
   print('Ваша основная еда это ' + food_choice)
   print('Главный охотник на этой территории ' + predator_choice)
   print(how_long_choice + ' спустя')
   live()
   print('')
   
   
main()
