# Python Coding

<br>

""" Author: Cooper (Jian) Li
    Introduction: 
   
    This game is based on <What if>, what if you born in another Parallel universe, what your life can be restarted. 
    
    This game is to help people feeling the moment, and cherish the present life.
    
    You will ask for chosing your basic ability value before you start your life.
    
    1) IQ
    2) Appearance
    3) Physique
    
    
    Bug: I couldn't print the fail()
    
    
    

"""
from sys import exit
import random


def start(): 
    
    print("""
    
    To restart your life, you need choice your basic attributes value from 1 to 3 before you start your life. 
    1 is lowest, 3 is highest. There are 3 basic attributes, IQ, Appearance and Physique.
    
    """)
    
    input("<Press enter to continue>\n")
    

  
    game_round = 2
    
    while  game_round > 0 :
        
        print(" What's your basic attributes value? eg: if you input 123, means IQ=1; Appearance=2; Physique=3")
        
        basic_value = input(prompt = "\n") 
        
        # Turn input into number 
        
        basic_value_str = int(basic_value)
 
        # Turn input into list
        
        basic_lst = [int(x) for x in str(basic_value_str)]
    
        print(f"\n You will born with IQ = {basic_lst [0]}, Appearance = {basic_lst [1]}, Physique = {basic_lst [2]} ")
    
        input("<Press enter to continue your new life>\n")
        

       
    # lucky boy
        
        if game_round > 0: 
        
            if basic_value_str == 111: 

                    print("""

                    1 year old: You were born.

                    5 years old: Your family is rich, so you can go to the noble Primary School.

                    10 years old: The teacher finds that you are not very smart, not good-looking, and frail and sickly, but you have received extra care from the teacher.

                    15 years old: Your body is too weak to walk, you can only sit in a luxurious wheelchair, but your parents did not abandon you.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: Your IQ is only 10 years old but you live happy.

                    25 years old: Aliens invaded the earth, and mankind began a decades-long war with aliens.

                    30 years old: Trump is 111 years old and he decided to run for president again, He wants to lead the war against aliens, will you vote for him?



                    """)

                    input(prompt = "Y/N \n")

                    print("""

                    Election year: Whether you vote for him or not, people all over the world think he is the only person who understands aliens best, so he became president again.

                    40 years old: The child of your elementary school teacher became a scientist and developed a super serum.

                    45 years old: Thanks to your elementary school teacher who is still alive, you were lucky enough to be selected as the first serum injection. Of course a lot of money was spent.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    50 years old: From then on, you have a super brain, and within 5 years you have learned all the knowledge and become the smartest person in the world. You have also gained the super power to control other people's thinking, but you still need to be in a wheelchair.

                    55 years old: People call you Professor X.

                    60 years old: In the end, it is not Trump who leads mankind to win the war with aliens, but you.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    65 years old: You find that you can live forever.

                    70 years old: The scientist who invented the serum was killed by an organization called Hydra, and the serum formula was accidentally destroyed.

                    75 years old: You find that there are only 10 people like you in the world.

                    80 years old: The 10 of you decided to form a group, called the Eternals, and try to protect the universe.

                    """)

                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <Lucky one>

                    We may not need so many superpowers. Plainness and misfortune may constitute our entire life, but God is fair, and He will always open another door for us. Feel your new life! ! !

                    """)

                    break


                # Joker    

            elif basic_value_str == 221 or basic_value_str == 231:

                    print("""

                    1 year old: You were born.

                    5 years old: Your family is not rich, your father is heavily alcoholic, and your mother suffers from domestic violence.

                    10 years old: Your body is weak, you are often bullied by your classmates, and your teacher doesn't care about you.

                    15 years old: You have been resentful for a long time. In order to retaliate against this society, you decided to join a local youth gang organization.

                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: You have been a gangster for five years but you are always a gangster.

                    25 years old: Your father perpetrated domestic violence against your mother, and in the end you couldn't bear it and took a knife to avenge your mother.

                    30 years old: Trump is 111 years old and he decided to run for president again, will you vote for him.


                    """)

                    input(prompt = "Y/N \n")

                    print("""

                    Election year: Of coures you can't vote, you are in the prison.

                    40 years old: You were released on parole because of good performance.You decide to start your life again, so you find a job.

                    45 years old: But life made a joke to you again, your mother was killed by police in accident.  

                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    50 years old: You decide to wear a mask and you always have a poker card in your pocket.

                    55 years old: You have become the most wanted criminal to the police, but no one knows who you really are.

                    60 years old: Now, people call you Joker.

                    """)


                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <Extrajudicial Fanatics> 

                    We may all have thought about starting our own life again. In the parallel universe, no matter how strong your ability is, your destiny will not develop in the direction you hope. So, live in the present, feel the present.

                    """)

                    break


                # GOD FATHER        
            elif basic_value_str == 321 or basic_value_str == 331 or basic_value_str == 312:

                    print("""

                    1 year old: You were born.

                    5 years old: Your family is not rich, your father is heavily alcoholic, and your mother suffers from domestic violence.

                    10 years old: Your body is weak, you are often bullied by your classmates, and your teacher doesn't care about you.

                    15 years old: You have been resentful for a long time. In order to retaliate against this society, you decided to join a local youth gang organization.

                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: Because of your high IQ, your status in the gang continues to improve.

                    25 years old: You have become the leader of the gang. You have much power to influence anything.

                    30 years old: Trump is 111 years old and he decided to run for president again, will you vote for him.


                    """)

                    input(prompt = "Y/N \n")

                    print("""

                    Election year: Whether you vote for him or not, he loss the election, the God Father, from Corleone Family, become the president.

                    40 years old: Your organization is oppressed by the Godfather, so you deside to start a war.

                    45 years old: The war last for 5 years.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    50 years old: Finally, you were shot by Corleone Family. 


                    """)


                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <No way no money> 

                    We may all have thought about starting our own life again. In the parallel universe, no matter how strong your ability is, your destiny will not develop in the direction you hope. So, live in the present, feel the present.

                    """)

                    break



                #Shiled

            elif basic_value_str == 323 or basic_value_str == 313:

                    print("""

                    1 year old: You were born.

                    5 years old: Although your family is ordinary, you are outstanding compared to other children.

                    10 years old: Tearcher finds that you are smart and strong, you have a Fast response on everything.

                    15 years old: Your parents die in a car crash, even though, you still Striving to live and start to study harder.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: You were admitted to the West Point Military Academy

                    25 years old: CIA is looking for the young kid for the future mission. You were chosen by CIA.

                    30 years old: Trump is 111 years old and he decided to run for president again, will you vote for him.


                    """)

                    input(prompt = "Y/N \n")

                    print("""

                    Election year: Whether you vote for him or not, He is the only one running for president  so he became president again.

                    40 years old: You were sent to perform multiple tasks, you performed well, and you finally returned with honour.

                    45 years old: The government has formed a new spy organization called SHIELD, and you are assigned as the person in charge.

                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    50 years old: LOKI invades the earth. Because Iron Man is too busy, Thor is drunk, Hulk and Black Widow get married and retired, you can only ask Superman and Batman from the DC universe for help.

                    55 years old: You protect the earth very well, so you decide to retire early

                    60 years old: Thanos came and snapped his fingers. you turned into the dust

                    """)

                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <Ill-fated>

                    We may all have thought about starting our own life again. In the parallel universe, no matter how strong your ability is, your destiny will not develop in the direction you hope. So, live in the present, feel the present.


                    """)

                    break


                #doctor

            elif basic_value_str == 322 or basic_value_str == 311:

                    print("""

                    1 year old: You were born.

                    5 years old: You were born in a scholarly family, and your parents taught you to read and write when you were very young.

                    10 years old: You are very smart in your class and very careful in doing things

                    15 years old: You got admitted to a good high school and submerged in the sea of questions


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: After your unremitting efforts, you were admitted to Harvard Medical School

                    25 years old: You become a young and famous Surgeon doctor. People call you Doctor Strange

                    30 years old: Trump is 111 years old and he decided to run for president again, will you vote for him.


                    """)

                    input(prompt = "Y/N \n")

                    print("""

                    Election year: Whether you vote for him or not, He is the only one running for president  so he became president again.

                    40 years old: The biggest gang fire broke out. The war last for 5 years. Until......

                    45 years old: One of the gang leader was seriously injured and was sent to your operating room. You failed to save him.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    50 years old: You blame yourself in the next 5 years. You decide not to be a doctor any more, and trying to find peace.

                    55 years old: You are looking for the peace for 5 years, and finally find a place named Kamar-Taj in Nepal.

                    60 years old: Your teacher Doctor Strange ask you to protect the earth from the future dangers.

                    65 years old: Thanos from multiple universe came and snapped his fingers. you turned into the dust.

                    """)


                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <Unexpected Life>

                    We may all have thought about starting our own life again. In the parallel universe, no matter how strong your ability is, your destiny will not develop in the direction you hope. So, live in the present, feel the present.


                    """)

                    break


                #super man

            elif basic_value_str == 333:

                    print("""

                    1 year old: You were born.

                    5 years old: Your father is a general and your mother is a physicist, The resources on your planet are drying up, and civil wars are constantly erupting.

                    10 years old: Your father was killed in the civil war, and your mother modified your memory and sent you on a spaceship flying to another plant named New 52.

                    15 years old: You have demonstrated a superpower that is different from that of the people on New 52.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: Your adoptive father was caught in a tornado, you inspired your superpowers and saved him. you know for the first time that you are not from this planet.

                    25 years old: Your save a lot of people with your power. And Known by the world. People call you supper man.

                    30 years old: Your appearance made the world know about the existence of aliens, you were recognized as a god by the world, and the traditional belief system collapsed. Extreme religious people openly oppose your existence.



                    """)
                    input("<Press enter to continue your new life>\n")


                    print("""

                    35 years old: You gradually lose yourself in the support of everyone, and your heart is gradually eroded by darkness. You begin to condone the criminals who support you, and the world is thrown into chaos.

                    40 years old: The Dark Knight identified you as the culprit who caused the chaos in this world, so he invented a weapon specifically designed to deal with you.

                    45 years old: The war is about to start, and you have no power to fight back under the special weapon in the hands of the Dark Knight. Unlike Batman in other universes, Batman in this universe did not show mercy. He eventually killed you.


                    """)

                    input("<Press enter to the life summary>\n")
                    print("""

                    Life summary: <You don't belong to this era>

                    We may all have thought about starting our own life again. In the parallel universe, no matter how strong your ability is, your destiny will not develop in the direction you hope. So, live in the present, feel the present.


                    """)

                    break




             # Hollywood

            elif basic_value_str == 233 or basic_value_str == 133 or basic_value_str == 132 or basic_value_str == 232 or basic_value_str == 332:


                    print("""

                    1 year old: You were born.

                    5 years old: You have a beautiful eye. Everyone says you can be a star in the future. 

                    10 years old: This year James Cameron is preparing to restart the Dune movie. This year James Cameron is preparing to restart the Dune movie. The crew is looking for the actor of the female number one.

                    15 years old: After 5 years of screening, (you know Cameron's speed), you finally won the role of Chani with your beautiful face and superb acting skills.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: After another 5 years, Cameron finally finish this movie, much faster than Avatar 2.

                    25 years old: Cameron spent another 5 years in post-production. The film was a big success and became the first successful remake of Dune,The film became the first successful remake of Dune, and you won the Oscar for Best Newcomer (a new award in the future) for this.

                    30 years old: At the peak of your career, Nolan is preparing to shoot Interstellar 2, and he contacts you to hope you become the heroine of this movie.




                    """)
                    input("<Press enter to continue your new life>\n")

                    print("""

                    35 years old: After 5 years, the filming of the film finally started, but unfortunately, the prop artist on the set was a newcomer. He made his debut last month. His mistake caused you to be shot by a prop gun on the set. You were unfortunately killed at the age of 35.


                    """)


                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <Beautiful flowers are soon picked>

                    We may all have thought about starting our own life again. In the parallel universe, no matter how strong your ability is, your destiny will not develop in the direction you hope. So, live in the present, feel the present.

                    """)

                    break



            elif basic_value_str == 112 or basic_value_str == 212 or basic_value_str == 113 or basic_value_str == 213 or basic_value_str == 122 or basic_value_str == 222 or basic_value_str == 123 or basic_value_str == 223:

                    print("""

                    1 year old: You were born.

                    5 years old: Your family is ordinary. You don't look outstanding.

                    10 years old: You don't have any lofty ideals.

                    15 years old: Your grades are very average.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    20 years old: You were admitted to an ordinary university.

                    25 years old: You graduated with ordinary grades in university, and then you got a job with a very ordinary salary.

                    30 years old: You married an ordinary person.


                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    35 years old: Your child is of average intelligence.

                    40 years old: Your friends have become rich men.

                    45 years old: You have been in your position for almost 20 years and have not been promoted.



                    """)

                    input("<Press enter to continue your new life>\n")

                    print("""

                    50 years old: Children’s expenses are very stressful for you, but your family is very happy.

                    55 years old: The company's founder's health becomes bad, but you get his extra attention during this time.

                    60 years old: The company's lawyer came to your home, You are told that the founder has passed away, and you are his only heir.  


                    """)

                    input("<Press enter to continue your new life>\n")

                    print(""" 

                    65 years old: You lived a prosperous life when you were 65 years old. But you know that all this is not true.

                    70 years old: You decide to donate all the founder's estate. Used for the development of poor areas.

                    75 years old: Your body is not as good as before, but you have found inner peace.

                    80 years old: You passed away peacefully at the age of 80, but your legacy remains in this world forever.


                    """)

                    input("<Press enter to the life summary>\n")

                    print("""

                    Life summary: <Lucky one> 

                    We may not need so many superpowers. Plainness and misfortune may constitute our entire life, but God is fair, and He will always open another door for us. Feel your new life! ! !

                    """)

                    break
                    
                    
            
                      
        
        elif basic_value_str == 211 or basic_value_str == 121 or basic_value_str == 131:
            
        
            fail()  
            
            game_round -= 1 

            if game_round == 1:
                
                                                          
                print(f"God give you {game_round} more chances.")
                    
                input("<Press enter to continue your new life>\n")
                    
            elif game_round == 0:
                                         
                print("You got no chance.")
                
                exit(0)
                    
            else:
                    
                print('Wrong!')
        else:
            
            print("Please enter number like 123 ")

def fail():
    
    print("""
    
    0 years old: Your physique is so weak that you could not survive in your mother's womb.
    
    Life summary: <Ill-fated> 

    There are nothing to summary, you die too fast.

    """)

                

start() 

<br>
