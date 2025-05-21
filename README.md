# rock.paper.scissor
rock.paper.scissor
import random
print("marhba bik f lo3ba d:\n (hajara/waraqa/miqas)\n")
choice=input("khtar hajara/waraqa/miqas\n 🪨 📃✂️\n")
ochoice=random.choice(["hajara","waraqa", "miqas"]).lower()

emoji_map = {
    "hajara": "🪨",
    "waraqa": "📃",
    "miqas": "✂️"}


if choice == ochoice:
    print("ta3adol cumpioter khtar" ,ochoice,emoji_map[ochoice])
elif choice== "hajara"  and ochoice== "waraqa" :
    print ("khesarti, computer khtar",ochoice,emoji_map[ochoice])
elif choice== "hajara"  and ochoice== "miqas" :
    print("ghlebti,computer khtar",ochoice,emoji_map,[ochoice])
elif choice== "waraqa" and ochoice==  "miqas" :
    print("khesarti,computer khtar",ochoice,emoji_map[ochoice])
elif choice== "waraqa" and ochoice==  "hajara" :
    print("ghelbti,computer khtar",ochoice,emoji_map[ochoice])
elif choice== "miqas" and ochoice==   "hajara" :
    print("khesarti,computer khtar",ochoice,emoji_map[ochoice])
elif choice== "miqas"  and ochoice== "waraqa" :
    print("ghlbti computer khtar",ochoice ,emoji_map[ochoice])
else:
    print("khetbti khatae")
