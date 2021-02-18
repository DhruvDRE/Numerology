import pandas as pd
import numpy as np

def numero(t):
    print("\n"+t)
    t=t.upper()
    l=[]
    m=0
    for i in t:
        l.append(i)
        m+=1
    #print(l)  
    s=0
    for j in range(m):
        if (l[j]=='A' or l[j]=='I' or l[j]=='J' or l[j]=='Q' or l[j]=='Y'):
            s+=1
        elif(l[j]=='B' or l[j]=='K' or l[j]=='R'):
            s+=2
        elif(l[j]=='C' or l[j]=='G' or l[j]=='L' or l[j]=='S'):
            s+=3
        elif(l[j]=='D' or l[j]=='M' or l[j]=='T'):
            s+=4
        elif(l[j]=='E' or l[j]=='H' or l[j]=='N' or l[j]=='X'):
            s+=5
        elif(l[j]=='U' or l[j]=='V' or l[j]=='W'):
            s+=6
        elif(l[j]=='O' or l[j]=='Z'):
            s+=7
        elif(l[j]=='P' or l[j]=='F'):
            s+=8
        elif(l[j]==' '):
            s+=0
        else:
            print("Kindly Enter Valid Input/Alphabets")
    print("The Numeral Total Of Your Name :" , int(s))
    aus=np.array([1,3,5,6,9,10,14,15,19,21,23,24,27,32,33,36,37,41,42,45,46,50,51,54,55,56,60,64,65,66,67,69,72,73,75,77,79,81,82,83,85,86,89,91,92,93,95,96,97,105,108])
    avgn=np.array([2,7,13,17,20,25,30,34,43,49,52,53,58,59,61,62,63,70,71,74,78,80,90,100,102,103,104,107])
    inaus=np.array([4,8,11,12,16,18,22,26,28,29,31,35,38,39,40,44,47,48,57,68,76,84,87,98,99,101,106])
    a=0
    avg1=0
    inaus1=0
    s1=int(s)
    if s in aus:
        print("Type Of Your Numerology Is :\nAuspisious")
    elif s in avgn:
        print("Type Of Your Numerology Is :\nAverage")
        a1=s
        avg1=1

    elif s in inaus:
        print("Type Of Your Numerology Is :\ninauspisious")
        a2=s
        inaus1=1
    else:
        print("invalid")

    if(avg1==1):
        s2=s
    elif(inaus1==1):
        s2=s
    else:
        s2=0
    #for checking distance from auspisious
    if(s2>0):
        l2=[]
        lent=len(aus)
        for k in range(lent):
            l2.append(aus[k]-s2)
        l3=[]
        for k1 in l2:
            if k1>-1:
                l3.append(k1)

        sug=min(l3)
        print("\nMeaning of Your Numerology:")
        real(s)
        print("\nSuggestions:")
        if(sug==1):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.A\n2.I\n3.J\n4.Q\n5.Y\n");
        elif(sug==2):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.B\n2.K\n3.R\n");
        elif(sug==3):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.C\n2.G\n3.L\n4.S\n");
        elif(sug==4):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.D\n2.M\n3.T\n");
        elif(sug==5):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.E\n2.H\n3.N\n4.X\n");
        elif(sug==6):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.U\n2.V\n3.W\n");
        elif(sug==7):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.O\n2.Z\n");
        elif(sug==8):
            print("\nAdd Any One Of This Letter To Your Name For Converting it Into An Auspicious Numerology Analytic :\n1.P\n2.F\n");
        else:
            print("\nIts Already Auspicious\n")
        
        print("Meaning Of Your changed Numerology")
        real(s+sug)
    else:
        print("Meaning Of Your Chosen Numerology")
        real(s)
        print("\nSuggesstions:It's Already Auspicious No Need To Add Anything")

def real(n):
  if(n==1):
    print("1. Beneficial: Number 1 gives popularity, name, fame, success, support, power, authority and rise to high levels. This number is very good for writers, poets, actors and leaders, best for people with birth or the destiny number 1,4 or 8")
  elif(n==2):
    print("2. Peace and harmony: number 2 denotes gentleness, peace, harmony and contentment. It is not good as material number. This number is assigned to residences and addresses of places of worship. ")
  elif(n==3):
    print("3. Good fortune: number 3 bestows popularity, humor, good fortune, name fame, leadership, success and good social relationship. No.3 persons are bold, intelligent, trustworthy, disciplined, tolerant hard-working, highly educated and good speaker." )
  elif(n==4):
    print("4. Secret enemies: Number 4 is not good as name number and should be changed immediately. It does not bring success, in business and material areas, the person is cautious, suspicious, lonely but popular. They have fears sicknesses and opposition.")
  elif(n==5):
    print("5. Progress: Number 5 gives popularity name, fem, positivity, progress, energy and charm and material success. The name continues to be remembered even after death. These people should cultivate perseverance and concentrate of mind. ")
  elif(n==6):
    print("6. Popularity: no.6 Osgood number especially for poets, artists, musicians and dancers. It gives them popularity, material success, Naeem and fan following. Series of no.6 is ideal for commercial use.")
  elif(n==7):
    print("7. Dreamer: Number 7 is good for the person who is scholar, writer artists reformer etc. Who have high principles and virtuous qualities? However, this number doesn't bring any material benefits as it makes the person a dreamer and impractical. Unexpected changes will take place.")
  elif(n==8):
    print("8. Delays and obstacles: number 8 is not good as name as it creates delays, difficulties, loneliness, obstacles, and nonfinancial benefits. This number will give great success in spiritual life. ")
  elif(n==9):
    print("9. Will power: Number 9 brings strength, determination, will power, energy, hardworking, intelligent, good luck and half from higher ups. It gives them fame, honor, wisdom, capabilities and recognition. It's also denotes travel, struggle against odd situations in the end.")
  elif(n==10):
    print("10. Wheel of fortune: Number 10 indicates rise and fall up and down, according to personal desire. It is a number of will power or likelihood . If a person wants something achieve good or bad -it is likely to materialize. Imagine and it shall be ordaining and it will materialize the power to manifest in inherent, but must be used with wisdom. Those names under This number will be dignified and popular. Confidence and patience co-exist in their lives but their fortunes will change frequently because of zero. (A good number)")
  elif(n==11):
    print("11. Difficulties and dangers(lovers): number of hidden trials and treachery. So called friends and well-wishers will not be true or loyal and oppositions several times. capabilities of inherent will be lacking there will be there will be a fear or illusion of separation. There can be interference from a third force which can be person or an idea. There will be e lot of obstacles and disharmony. Those having 11 as their name number will come up in life by their sheer faith in God. (not a positive number)")
  elif(n==12):
    print("12. Sacrifice, suffering and anguish: the person will be sacrificed for the plans of others. Lot of mental anxiety, emotional stress, anguish and forgetfulness. This number stands for sacrifices, to learn lessons in this life. Name number to 12 people naturally possess the ability to attract people by their power of speech full stop they sacrificed their life for welfare and happiness of others for soldering their burdens too (not a very good number)")
  elif(n==13):
    print("13. Changes in plants and places: Indian numerology believes 13 is a number of willpowers he who understands how to use 13 will dominant in western numerology it is a number of upheaval and difficulties that is associated with power which is used for selfish purpose and will bring destruction upon itself. There is a warning of the unknown and an unexpected. such persons have power, but must use it with care. (this is not desirable number)")
  elif(n==14):
    print("14. Monetary gains through changes: it is a member for speculative matters which brings ‘luck'. It also indicates movement and travel which will be fortunate. It's a mistake to rely on others. The person has to be prudent and cautions always.14 numbers can bring luck in gambling, betting, lottery etc. Defense risk from thunder water fire lightning (five elements) this number can be called a very lucky number.")
  elif(n==15):
    print("15. magic and magnetism (magician): it is an extremely lucky number and attract the public towards the person it based on the persons magnetism and charisma. It is fortunate for obtaining money guts and favors from others. Such persons are good in communications, romance, lovers of art music and drama. Though this name number is not conductive to leading virtuous life it is one that is ideally suited for a purely materialistic one. Life will be luxurious. If their birth number is also favorable, this people will attend fame, wealth and distinction in life. (brilliant commercial number)")
  elif(n==16):
    print("16. danger of accidents and defects of plants (tower): it was of fertility also danger of accidents and defeat. There will be a confrontations and showdown. Life is a story of failures. if the name equals 16, it would obviously be wise to change the spelling of the name to avoid this vibration. This number signifies speedy progress and sudden downfalls.")
  elif(n==17):
    print("17. Success after great trails of time.( star) : it is the image of love and peace and promises that the person or entity which represents with right superior in spirit to the trials and difficulties of early life with the ability to control their former failure in personal relationship and career that is a number of immortality and indicates that the person or entity will leave after him. this name number will give permanent prosperity and great film. This people will reach their bodies and lives to reach their goals and will ache enormous prosperity. The world will never forget them. This number can give mystic powers. (both positive and negative number)")
  elif(n==18):
    print("18. Treachery and accidents (moon): this number represents bitter quarrels in family and work place. It warns of accident and mishaps. Money does come but only after quarrels and litigations. It the name add to18 it should be immediately changed. (A very negative number)")
  elif(n==19):
    print("19. Most fortunate and favorable number(sun): it bestows the person or entity with happiness, success and fulfillment - success in family and work it indicates over all failures and disappointments number 19 reaches I said is highly honored. This number indicates the rising sun, position, status, happiness success and willingly be on continuous rise. They will look young and will be very active even in their advance age (most brilliant number)")
  elif(n==20):
    print("20. Delays and obstacles (judgement): this number is for powerful awakening upbringing new purpose, new plans and new ambitious working for some cause ideal. There may be delays and obstacles in fulfilling your plans. It is not material number and does not give financial success. The 20-number people will Excel in medical practice using toxic medicines and deal with poisonous drugs (not a desirable number)")
  elif(n==21):
    print("21. Success advancement and honors after testing (world): this number promises awards, rewards, name, same and general elevation in the life and career. It indicates victory after considerable effort and time, 21 is a number of ceramic rewards after much soul testing. It's about ultimately getting what you always wanted. The struggle hard in there early days but achieve success and happiness as they grew up. They will attend good position permanently in their lives. (A good number)")
  elif(n==22):
    print("22. Illusion and delusion: it indicates a person who lives in fool's Paradise, dreamer of dreams who awakens only when surrounded by danger. It wants of mistakes in judgement of placing faith in those who are not trustworthy. The person should exercise caution and watchfulness. The person haul use mind power to the change his destiny. This number instigates base feelings and emotions. They are drawn towards gambling, drinking, speculation and other vices and we'll readily indulge in them. They invariably earn a bad reputation. They often once humiliation (pain key tune number)")
  elif(n==23):
    print("23. Success Fame and protection from superior and high places: it's the most fortunate number and blesses the person with abundance and grace in personal life and in career. It is a number of Karmic rewards. It also guarantees help and protection from high places. This people will find success in all their endeavor’s. They can achieve Achy things which others would not even dare to imagine. They will successful in earning them patronage, respect honor and favor of people in very high position (a very fortunate number)")
  elif(n==24):
    print("24.  Financial success, love and happiness: this number blesses the person with money love and creativity. It is a number of Karmic rewards.  it promises assistance of this with power and close Association with people high rank and position full stock it promises gain through romance and magnification which is extremely attractive to the opposite sex. These peoples can be found progressing very fast in uniform service like defense, Paramilitary forces and police. Even if they join in the lower rank in any field, this number will help them to rise to very high position by sheer fortune (A very good number)")
  elif(n==25):
    print("25. Spiritual wisdom-ultimate success after years of difficulty: it is favorable number, which indicates over coming dis-appointments in early life and learning from past mistakes. Financial benefits come after hard work but this number is very good for persons in spiritual growth. They are worldly wise, known for clarity of thought and hence their actions will be well-planned. The lives of these people will end with respect and honor after many trials.")
  elif(n==26):
    print("26.Struggle due to association with bad friends: It warns of dangers, disappointment, and failure especially regarding ambitions due to bad advice. It talks about unhappy partnership and marriage. Name no. 26 denotes poverty in old age and fruitless efforts. They will undergo great losses due to friends and partners. (A negative number)")
  elif(n==27):
    print("27.Excellent harmonious and fortunate number of power and enchantment: It assures gains & rewards, authority and command, this number assures of success from productive activities. Name no. 27 signifies a clear mind, intelligence, hard work, accumulation of wealth; all round influence and positions of prominence & high rank. Especially in uninformed services like police, army, etc., they will be respected and treated as the best in their profession or service. (A no. for power)")
  elif(n==28):
    print("28.An unlucky number of frustration and contradictions: The number 28 does give success but with likelihood of losing everything. It indicates loss through misplaced trust, powerful opposition from enemies, and danger of losing court cases, life will start over and over again. If the name number is 28 it should be changed immediately.")
  elif(n==29):
    print("29.  Very unlucky number of treacheries, consent uncertainty and deceit: it is the number of trials and tribulations, unreliable friends’ coma unexpected dangers, griefs and anxiety caused by number of of the opposite sex. It is a number of grave warnings in personal and career life. If the name number is 29 it should be changed immediately. Those under this number often find it necessary to go to court to settle disputes. (A very unfortunate number)")
  elif(n==30):
    print("30. In different numbers not material is beneficial: it is neither fortunate nor unfortunate number as it depends on Desire of person it represents. The person with this number has very few friends, the train to be loners. the people with this number are wise thoughtful but in a world of fantasy. (An average number)")
  elif(n==31):
    print("31.  Net beneficial materiality: the person with this number through a genius and intelligent loner and denoted. This person will retract from society at some unexpected time. The reason has strong opinions, and remains fix in personal habits. They have interest in strategy philosophy and occult Sciences. If their birth number is one of any months, this number help them to achieve great position in their official career. (An unpredictable number)")
  elif(n==32):
    print("32. A good number for communication:  number 32 present wisdom and powers of mother goddess (Mohini Siddhi). The number has magical powers to sway the masses and get help from high positions. This number is good for people in advertising marketing and PR. The person can also work under pressure. They come cut with unique ideas and take me even without prior experience. The potent and powerful number can make anyone a prominent person. This number is said to be as epitome of wisdom and intuition. They will attain high position in life & will be youthful in appearance even in old age (very divine & creative no.)")
  elif(n==33):
    print("33. Financial success and commercial number This number blesses the person with money, love and creativity. It is a number of karmic rewards. In Indian numerology ancient text attribute this number to the goddess of wealth, Mahalaxmi or her male counterpart Kibera. This number signifies simultaneous growth in divine grace and prosperity. Along with divine grace; they are blessed with abundant wealth and properties. They will have many luxurious things at their disposal. They all have everlasting wealth.")
  elif(n==34):
    print("34. Spiritual wisdom -ultimate success after years of difficulty: If not material number, financial benefits are difficult. Their mind easily succumbs to serious pleasure. Hence, they are advised to change this name to a more fortunate one. (Unfortunate no.)")
  elif(n==35):
    print("35. A number of Struggles and difficulties. These people will become very rich and popular but later lose all their money. This number helps in earn no money through illegal means. They will be fickle minded. This number would create health issues. Those with this name number must be very careful in their large wishes Endeavors. (A negative number)")
  elif(n==36):
    print("36. Excellent harmonious, fortunate number of polar enchantments: It assures gains & rewards authority & command, this to assures of success from productive activities. 36 number brings power & success should be used wisely.")
  elif(n==37):
    print("37. A good number of happiness and success:  It is good particularly for dealing with opposite sex. Love, romance, Good fortunate friendships. Happiness and success are easily attained when in partnership with other than when operating alone. This is very lucky number. It will lift end ordinary person to the most prominent position in life. People will come forward to give their capital with such people & accumulation of money & wealth will be easy through KHURAANA tours means. They will have an active interest in the fine arts & will, in allege ad comfortable & luxurious lives. They will be renowned for their pleasing grace pleasant looks & attractive manner of speaking.")
  elif(n==38):
    print("38. Difficulties and dangers (Lovers): Number of hidden trials. So called friends and well-wishers will not be true or loyal and will face oppositions several times. Compatibility of Hacking there will be a fear or illusion of separation. A very unlucky tuner-treachery, uncertainty and deceit. It is a number of heaviest Karma of all.")
  elif(n==39):
    print("39. Indifferent number not materially beneficial: It is neither fortunate nor unfortunate. The person with this number has very few friends, they tend to be loners. Mentally the person should be superior, sincere, hardworking & capable of logical and thoughtful enjoyed by others. They are not healthy as the other 3 number people & are prone to some kind of diseases.")
  elif(n==40):
    print("40. Not beneficial materially: Name no. 40 earns good friends, who will be of immense help to them in gaining jobs and positions of distinction. It provides accumulation of fine jeweler Their will turn out to and wealth. But they will lose all their wealth eventually. lives and end will be in misery. ")
  elif(n==41):
    print("41. A very good number: Name no. 41 denotes the quality of charming and controlling.  They will be renowned achievers and ill have high principles. They will be keen about their development and will be world famous. They will lead successful lives.  41 is very lucky number.  It begets people's support, a luxurious life, and abundance of wealth. This number will prove to be very lucky big corporate house having large turnovers.")
  elif(n==42):
    print("42. Financial success, love and happiness: Name No. 42- those names under this number, even if they are poor at the beginning of their lives, will attain very prominent rank or position in their careers. ill attain They will have a thrifty bend mind and are smart in saving money. Strength of mind and grace will flourish.  (Very good commerce of no)")
  elif(n==43):
    print("43. This is strange number. People with this name number will be revolutionary.  Whatever profession in which they are involved, this number will produce new enemies. They will have the tendency to resign from their jobs often speaking and out extreme ideas. They will have extraordinary powers of imagination, speaking and writing. Their desire will be fulfilled at the end. This is regarded as unlucky, as indicates trials. Their shrewdness increases with age, put they will encounter more opposition than support. (Not a fortunate number)")
  elif(n==44):
    print("44. Struggle losses, difficulties and delays. Yameeb.44 helps in earning money easily. Industries involving many people like cineraria, heater, printing presses, coal and iron mining, painting making future and sports goods, and organizing contests will earn them good income. Hiring out vehicles of transport also be rewarding. They can also run banks. One day everything will be closedown. This number indicates that they will have to spend some time in prison Then mind will go astray in bad ways. (Not a lucky number)")
  elif(n==45):
    print("45. Excellent harmonious and fortunate number of power and enchantment: It assures gains and rewards and command; this number assures of success from productive activates people representing 45 should always carry out their own original ideas and plans and not be influenced by others opinions. It is a number of karmic rewards earned more one incarnation. Name No. 45 is a lucky number.")
  elif(n==46):
    print("46. Excellent indicating a Prince / Princess life: This has been described as the “forehead below crown” in the ancient texts. Whatever may be the business; this tender will help one to reach the pinnacle of success. Wealth and status will go up with of age. Good and fortunate friendships, love and' romance and harmony in relationships. This number is associated with great inventions, scientists and Idea.")
  elif(n==47):
    print("47. A very unlucky number of treachery uncertainty and deceit: It tests the person through trials and tribulations, unreliable friends, unexpected dangers, grief and anxiety caused by members of the opposite sex. It is a number of grave warming in personal and career life. Name no. 47 persons come up very fast in life. If the name number is 47 it should be changed immediately. (A negative number).")
  elif(n==48):
    print("48.  Indifferent number not materially beneficial: Name no. 48 will be more interested in religious matters. they face opposition in matters that involve the society at large. they will do a lot of work for public welfare. these people create problems for themselves while attempting to do things beyond their capacity. Fate is against them most of the time.")
  elif(n==49):
    print("49.  A good number. (Use of this number should be done if birth no. is good), Name No.  brings abundant riches, fame, achievements. They lead highly eventful lives, travel a lot of have wonderful experiences, permanent prosperity, and excellent properties and have sudden fortunes. If the birth number is a fortunate one, they lead happy lives. If at then  their life will end in a tragic manner. It makes the person a pessimist, a loner and cutoff from society.")
  elif(n==50):
    print("50. It's a fortunate number: They will have great success in many occupations. They will eloquent, powerful leadership qualities.  They will be a life of intense and constant activity. They have a magnetic personality, fearless, intelligent and good at multitasking. They excel in educations. These people will be lucky after the age of 50 their life span will improve and they will live long. ")
  elif(n==51):
    print("51.it signifies sudden progress and a number of energies. Those who were just commoners yesterday will become popular and prominent overnight in ascent of rank and status. their body and mind will be bubbling with energy and become uncontrollable, this people will be ruled by extraordinary energy or power of both body and mind. This number is considered to be fortunate; it signifies the accumulation of abundant wealth. (It is a brilliant commercial number)")
  elif(n==52):
    print("52. This number signifies some type of revolutionary qualities. If the birth number is favorable it could bring world renown. if they are in the spiritual path, they can attain great powers, charm, and immense popularity. All their desires will be fulfilled. They can bring out new era in the life of others. It’s not materialistically beneficial number.")
  elif(n==53):
    print("53. These people will experience success and failure simultaneously. As they grow older, their lives will become steadier and they will become well known. Though these people are intelligent, popular and famous they are bound to get into problems beyond their control. (this is an unstable number)")
  elif(n==54):
    print("54. This will give success step by step. Failures can also happen. They will begin their lives with prestige, reputation and prosperity. Stubbornness, greed and decisions will make them lose their name and fame. Their life will be without freedom and they will be under the control of others. (it is an average number)")
  elif(n==55):
    print("55. This number indicates creation and destruction. This number is the epitome other of will power and intuitive knowledge. People under this number will astonish other by their knowledge and win them over. Wisdom, knowledge and intelligences will develop. If not used in the right way, this may destroy them. (this is an important magical number).")
  elif(n==56):
    print("56. This number is full of wonders. This number brings fortunes and fame.  It is a brilliant number for occultism and divination. this number can free a person from all ties and can break bondage of any kind. This number is ideally suited in public relations, politics and in mass media. And can break bondage of any kind. This number is daily Suited in public relations, Politics in mass media.")
  elif(n==57):
    print("57. High rise and fall: This number gives victory or success in the beginning but brings about gradual downfall and loss of interest in the end. Lile which progresses at a very swift pace will grind to a halt all of a sudden. People named under this number will achieve great heights from humble beginnings but will later revert to their original positions.")
  elif(n==58):
    print("58. This number gives outstanding popularity and the power to captivate others They are great achievers Life’s progress will be swift. They are pious, orthodox, great reformers, and are more attached to religion. If their birth number is 4 or 8 or any normal they will hold positions of great responsibility and fame. Outwardly these people appear to be very lucky but they also have a lot of unwanted fears within. They may be involved in education, engineering. medicines, sciences, or research.")
  elif(n==59):
    print("59. These people will be research-minded: Their writings will be full of humor and they would become rich by writing and will have excellent pubic support their aim will be to earn money and enjoy permanent fortunes. They may suffer from nervous diseases Including paralysis. They will be successful in advertising, communication, film industry, publicity.")
  elif(n==60):
    print("60. This number signifies. Peace prosperity, appreciation if fine arts, a balanced state of mind and wisdom. They will be skilled; station lists who can put fourth very logical arguments. Their family life will be happy and idealistic. This is quite a fortunate number they will be successful in education, travels, banking, photography, meditation, law or adviser. People with this same number will be the life of a party and highly popular.")
  elif(n==61):
    print("61. These people will get a comfortable Life and try new avenues according to their wishes. Success and failure come in cycle.They need to take care of their health it wins prestigious posts. come in cycles. They may seem to be leading happy lives, in reality, they will be unhappy in their family lives. They will spend much to achieve victory.")
  elif(n==62):
    print("62. This pruner will give great fame, victories and comfortable _life, but create enmity in family and relatives. At times, great dangers Arnd tailors alternatively affect them Intellectual faculties will improve. This name number can even help charming enemies These people do their jobs with concentration and devotion. They excel in the suppress of defense, journalism, research, publicity. From modest start they rise to great region.")
  elif(n==63):
    print("63. This number will lead one into wrong ways: The ancient texts describe this number as one related to thieves but they are, also missionaries and reformers. They donate generously and do a lot of social service. They e passionate about working for the cause of those who are suffering.")
  elif(n==64):
    print("64. This is good number of individualities: Opposition will be experienced in life with equal number of friends and foes. This number gives extraordinary will power, intelligence and acknowledge but anger, this will fetch fame by enabling them to do impossible things. This ensures high positions in the Government. At times, this will give such a high position that everyone will pay respect and hold these people in high esteem and awe.")
  elif(n==65):
    print("65. This number denotes divine grace and progress in spiritual life: let will exam the help of wealthy and powerful patrons. Marital life will be blissful. Persons under this Name number will be sometimes injured in accidents. They are best suited for mechanical or electrical engineering, water distribution, printing, atomic energy.")
  elif(n==66):
    print("66. A very auspicious number: This number denotes dynamism and oratorical skills, perfection in the fine arts patronage from the government authorities and also a comfortable life. They earn the name, fame, respect, trust and honor in society. They are very aristocratic. They are ideally suited for iron and steel industry, medicine,telecommunications, atomic energy, motor spares parts, transpiration and agriculture")
  elif(n==67):
    print("67. These people are artists and work with great determination amigo. They are patronized by power barons and they reveal noble ideas. should control them passions and lust for women. Love, affection and grace make the people endearing. It is an auspicious no. these persons do not any antecedent lies and cheating? They always speak the truth.")
  elif(n==68):
    print("68. This number is an average number. However, life starts quite pleasantly can suddenly grind to halt. They will get involved in schemes that they cannot achieve and will be badly hurt. Their greed alone will spoil them life. They need to be very careful in life. Even those who started as poor become rich")
  elif(n==69):
    print("69. This is a king's number: The person named under this number will be like an uncrowned king, in any business they involved in. They will be majestic in appearance royal, charming. very prosperous and will achieve awe-inspiring status, extremely comfortable and luxuriousness lives being emotional by nature, they are known to spend money lavishly for their self-satisfaction this very auspicious no. these. People rise in ice by them simplicity, hard work and efficient.69 Is associated with fortune honor and fame.")
  elif(n==70):
    print("70. People represented his number will be of extreme nature: Their comfortable life will get disturbed by circumstance. There will be frequent disappointments, failures and problems but be years will be fruitful, successful and filled with blessings. This number does not prose much power. If the destiny number is favorable, these people will be Happy due to their final years. it not, their problems may drown them in misery. These People rise up and up in their lives.rears will be fruitful, successful and filled with blessings. This people  up in their lives. They are admirers of beauty. They excel on foreign trade export.")
  elif(n==71):
    print("71. This number which brings about obstacles initially will later shower prosperity:They will be good counselors to others because of their intelligence. This number may be considered fortunate. They will face problems in both worldly affairs and health. Life is full of rise and fall.")
  elif(n==72):
    print("72. This is the best of all numbers under 9: Although these people struggle in their early years, they later enjoy life with all comforts, A mind devoid of doubt will be filled with joy.The wealth acquired by these people will remain intact in their family for many future Generations. Money will keep on coming continuously, without fail. (Businessman should take note of this advantageous number). It will also bring repute. This number signifies permanent wealth. These persons occupy high status and are good for polices. They may have some family issues. This no. benefits especially in vehicle spares, transportation,communication, medium, chemist and druggists")
  elif(n==73):
    print("73. This number strengthens mental faculties and bestows fame wealth and power:People having this number will aspire to lead comfortable lives and will accomplish them desires without anybody's knowledge. Support of the people in authority will be obtained and material possessions will be in plenty. If they are not honest, they will lose their fame.If they are the spiritual type, they will lead a peaceful and aristocratic life with pure fine arts and noble thoughts.")
  elif(n==74):
    print("74. These people will have area affinity towards their religion: They short of money often. They will introduce social and religious reforms and spread their principals. However, this is not a desirable number. This Name number is best suited and priests and is not favourable to others. These people always be in something or the other. These people always remain in work")
  elif(n==75):
    print("75. All of a sudden, they attain great fame: They will make good friends very soon  Unexpectedly, they become very popular. Fame and comforts will come in search of them They become good poets and writers. This is a charging number.")
  elif(n==76):
    print("76. Those having his-name number lost all their Worldly possessions at some point of time: They are very popular. They will be peaceful in philanthropic deeds. Surprisingly they make money in new ways. Income comes in through unexpected ways and will be blessed. This grace will be utilized to grammatical gains. Their last years are generally spent in solitude, doing nothing but eating and sleeping")
  elif(n==77):
    print("77. This number denotes increase effort, self-confidence and hard work: others will bring in fame and honour. Life Life will be very enchanting. They will reap full benefits only if they repose faith in God. They will have chances to travel abroad and do well foreign trade.")
  elif(n==78):
    print("78. They were in most righteous type among all 6-number people: They will have a great learning Towards their religion and orthodox beliefs. They can become good poets and listeners under their spell. They can be very generous and will be fond of social service. They can earn or inherit large sums of money very easily. But if they are not careful lose all their possessions expect the Divine grace. They Should lose all there attain success MANTRAS and will be respected by one and all in society. It is not a materialistic number")
  elif(n==79):
    print("79. People of this number tend to suffer very badly in the beginning of their lives with many difficulties: Later, these people will rise up quickly by their cleverness and sheer willpower. They will settle down very comfortably and will succeed in their endeavours. They will have popular support, a comfortable I life and will achieve enduring success. They become very fortunate with the passage of time and also become great personalities.")
  elif(n==80):
    print("80. This number has strange mystic powers, but may lead to grave dangers if the date of birth is not favourable:  Research in theology will be successful. Nature will change its course and help them. Though their lives will be full of dangers and anxieties, life will generally be comfortable. Miracles will happen. It is fortunate number. From being materialistic people, they become spiritualistic persons.")
  elif(n==81):
    print("81. This number signifies a fortunate life: This will give development, good position and wealth. If these people are not careful their luck could change for the worse. They will have opportunities to become teachers/ Preacher/ Lecturers.")
  elif(n==82):
    print("82. This is the most powerful number and it can even elevate and ordinary person for the status of a ruler: Those have this number in their name are duly conscious who with unceasing efforts, will dominate and rule life like lord Indra. They will own lands, gold mines and precious stones. They will be lovers of bred horses and will attain the pinnacle of fame. They will create unnecessary problems in their love matters and will be excessively adamant in nature. Their eyes will have magnetic powers. If the power of the number is properly understood and practised, the Yogic art of floating and walking on water can be mastered.")
  elif(n==83):
    print("83. This name number will bring prestigious post which will on respect and adoration of many: They will achieve a life of splendour and authority. This people will be successful. A very fortunate number.")
  elif(n==84):
    print("84. Early days will be full of struggle and worries. They earn enemies unnecessarily: Travelling benefits them. They do not get rewards commensurate to their efforts. They improve themselves to some extent spiritually. Though generally lagging enthusiasm at first, they can go to extremes, if needed be! If the influence of their birth date if favourable, they can be great achievers.")
  elif(n==85):
    print("85. The name number signifies those who come up the hard work: They not only overcome all afflictions, but help in solving other’s problems too. They reveal new ideas about religion and nature. They shine well in the field of medicine. They generally attain a position of distinction and honour.")
  elif(n==86):
    print("86. This number denotes those who come up in gradual manner and the hard way: They will get what they deserve. They will earn the favour and help rich people. With the help of others, they will lead a comfortable and happy life. They will have good savings and lead happy lives.")
  elif(n==87):
    print("87. This number can give mystic powers: Money will be earned by devious & illegal means. In case of a “negative swing”, this number make people steal at midnight and helps them to charm snakes and control animals. If birth and destiny numbers are not positive, this number can be related to criminals and other bad elements. If the same no. sums to 87 it should be changed immediately.")
  elif(n==88):
    print("88. This number gives spiritual progress: They will be generous and compassionate. They will be affectionate to all creatures. They will earn great fame. ")
  elif(n==89):
    print("89. This number, which also signifies benefits, will bring problems initially: They have a helping tendency and they will acquire great riches like land, houses and jewellery. Women will be attracted to these men. Society will respect the women of this Name number. They have combination and wealth. They lead fearless lives with the help of their great power of speech and action. Initially, fire, accidents may occur in their lives. It is a fortunate number.")
  elif(n==90):
    print("90. As this number derives its full power from the number 9, its people will go to any extent to get their desires fulfilled. Victory will be certain. They will become very wealthy and famous. For those who are interested in spiritual pursuits this number is not desirable.")
  elif(n==91):
    print("91.")
  elif(n==92):
    print("92. This number signifies god, silver, land, wealth, and possession power: It is a good number for material gains and spirituality. If people having this Name number can carefully practice the art of yogic breathing; they may even acquire acquire the power of Astral projection (defying gravity) or Kechari Mudra (defying diseases and death).")
  elif(n==93):
    print("93. These people are capable of doing marvellous things: They improve their worldly knowledge and are lucky to have their desires fulfilled. They exons in the field of histrionics through which they attain more fame. They earn through many business pursuits and lead very dignified lives.")
  elif(n==94):
    print("94. These people execute lots of good service for the sake of mankind in general: They bring reforms in society. Comfort and fame will come and go in their lives. Their fame and good work will generally be remembered even after their demise. This is a fortunate name number.")
  elif(n==95):
    print("95. This number signifies a disciplined life combined with daring events and honour: They will be successful in trade and will achieve distinction. They will earn riches by trading in a variety of new things. They will be excellent orators and get wide publicity. ")
  elif(n==96):
    print("96. This can give a combination of prosperity and higher education: All desires will be fulfilled. They can excel in the fine arts easily. Women will be charmed easily by these people. This is a fortunate number.")
  elif(n==97):
    print("97. This number gives proficiency in the scriptures and fine arts: It also gives eminence in a spiritual career. They will be successful in all their efforts and will be prosperous with astounding achievements to their credit.")
  elif(n==98):
    print("98. Like those of number 71, these people will also be intelligent: Their lives will be filled with worries and desires: Though they are intelligent, they may not benefit from that quality. Problems and permanent diseases will manifest themselves.")
  elif(n==99):
    print("99. This name number will lure its native to devious ways: Success will come along with enmity. This number signifies attacked by enemies, and hence it is not a good number. (However, they will be blessed with education, wealth, and prosperity).")
  elif(n==100):
    print("100. Even though this number is capable of giving success in all efforts, it will not offer many opportunities: There will be plenty of money. This number implies a long and comfortable life, without any major achievements.")
  elif(n==101):
    print("101. Those under this Name number will have greater help from governments or the people of authority (than from their own efforts). There will be lots of obstacles in their business. Slump in business will be common. This cannot be considered a lucky number.")
  elif(n==102):
    print("102. This number signifies success at first, followed by struggles and confusion. These people cannot be called lucky.")
  elif(n==103):
    print("103. This Name number is also favourable. There will be improvement in material prosperity initially, followed by a change in business. They will face a lot of completion. Later years will be pleasant and comfortable.")
  elif(n==104):
    print("104. This number will bring an upward spurt in life followed by unexpected changes. Though they can be good achievers, they can only earn fame and not money.")
  elif(n==105):
    print("105. This number can give fortunes, satisfactory environment, great fame and accumulation of wealth. It will beget good progeny.")
  elif(n==106):
    print("106. There will be marked changes in life: They will experience many problems during their middle age. Their later years will be comfortable. They get into deep troubles that cannot be solved easily. This number is not lucky one earned for worldly things will supersede the interest in seeking divine grace.")
  elif(n==107):
    print("107. This number will bring fame and success. If they are men, they will have problems due to women and if they are women, it will be for men. Even if they attain wealth, life will not be comfortable. However, they will be famous and influential.")
  elif(n==108):
    print("108. This number can give high position and success. Everything will happen according to their desire. As this number will induce its people to make good efforts resulting in success, it is a lucky number.")
  else:
    print("invalid")

def both():
  n=input("Enter Your First Name:\t")
  m=input("Enter Your Middle Name:\t")
  s=input("Enter Your Last Name:\t")
  compa=input("Enter Your Company Name:\t")
  l5=[]
  l5=compa.split(' ')
  print("Analysis For Your Company Name:")
  numero(l5[0])
  numero(compa)
  print("Analysis For Your Name:")
  fl=[numero(n),numero(n+' '+s),numero(n+' '+m[0]+' '+s),numero(n+' '+s[0]),numero(n+' '+m+' '+s)]

def name0():
  n=input("Enter Your First Name:\t")
  m=input("Enter Your Middle Name:\t")
  s=input("Enter Your Last Name:\t")
  print("Analysis For Your Name:")
  fl=[numero(n),numero(n+' '+s),numero(n+' '+m[0]+' '+s),numero(n+' '+s[0]),numero(n+' '+m+' '+s)]

def comp0():
  compa=input("Enter Your Company Name:\t")
  l5=[]
  l5=compa.split(' ')
  print("Analysis For Your Company Name:")
  numero(compa)
  numero(l5[0])

def destiny():
  #Destiny Number Calculators
  a=input("Enter Your Birth Day")
  b=input("Enter Your Birth Month")
  c=input("Enter Your Birth Year")
  s=0
  dn=0
  for i in a:
    s+=int(i)
  for j in b:
    s+=int(j)
  for k in c:
    s+=int(k)
  for l in str(s):
    dn+=int(l)
  if (dn==1):
    print("People of this Destiny number are really good fortunate. They have fair complexion, good built tall and have splendorous body. They know art of living. Whatever they desie to do. Only they must get an opportunity. But they find out opportunities also and arrange required paraphernalia ti the job. They have qualities of leadership also. This quality is put into effect when they are holding some government post or managerial post in the word of politics. At times some problems spring up due to their owm doing for example some people might not relish these natives to come forward and grab each opportunity in there hands. Such disgruntled people might create problems and thus the natves get caught indirectly in their own web. Financially they are they eam enough money but use judiciously, invest it in right channels, and spend the money on the family and household. These people are experts in making friends and maintaining friendship . They are only too willing to help their their friends as gets they can in hours of need, but also get busy in futfilling their ardent wishes. They are extroverts and do not like solitude. They can be successful business and successful  officers also. In fact can handle any mater pertaining to management and direction")
  elif(dn==2):
    print("Native of spiritual number 2 are excellent  speakers as if goddess sarswati is residing  in their tongue. They hypnotize listener with their arguments, grip on the subject and their lucid style. But they are obstigate right or wrong they do not budge do not budge an inch from their beliefs and argue with people. They are very fit as lawyers. They can give such a twist to an ordinary matter issue. Then they argue for or against the issue. As they are capable of breaking mountains of a mole, put forward such convincing logic and that To so effectively the  in others have no options but to agree with them. Thus their popularity goes to increase. These people shirk torm taking any responsibility. They leave everything to family and remain aloof free from problems of household. They are cheerful and love nature. In reality, there are two versions of their personality is individual dual and other public. In individual or personal life they do not acceptncy but in the public life they put up most ideal example of dutifulness and responsibilities. Public image their pleasures is marvelous. They join  people's in pleasure and goddess Laxmi enters their home through many doors. That is why they like to across wealth. From the point of view of finance they are really affuent. Their friend circle is which includes people form all age groups. In their own age group they aré already popular. They are very successful in medicine, animal husbandry, cosmetic and real estate areas. Men of Destiny 2 must correct some of their shortcomings. They should be too sentimental, This might tarnish their character. Always in a hurry and restessness are weak links of their nature. Thoy should do things after thinking. This would be in the interest of all concerned.")
  elif(dn==3):
    print("Ambitious people are sky rockeing They dream of turning possible. Nt only that they are too excited to execute such dreams However circumstances take such a tum that their dreams are shatered. They were. A result of al the hard work goes waste. But we must admit natives are optimists and think positively. They find thelir way through adverse situations. They hate to do things where there is no challenge, excitement or manliness that they are recognized and make progress also. In financial maters they achieve success very late and after much effort , but the success is solid. But alas, misforess is spestons.The philosophy of destiny no. 3 people, money is more important than  friendship  they are practical and know that without money all other things have no meaning and nothing can be, achieved you do not have money. And yet They are normally in good shape, but even if there is mind pair or cold they will exaggerate it. Normal disorders ke indigeson gas problem hectic routing in there life . They have quaites of inspection, investigation, testing they look at everything  from diferernt angles and minutely and are able to point their nerits and faults.  Best area for them is wholesale or retal trading, readmade garments,agency, franchisee, broker, exchange, money lending etc where they make process   and live life free from financial worries. So far of their defects short  coming wories So far their defects short  comings are concerned they are touchy and get depressed in minor matters . They should get out this weakness")
  elif(dn==4):
    print("This number stands for peace and rest natives of this number are of stable mind, serious mild and tolerant and do not lose patience  in adverse situations. They are cooling People tempered and do not make have cry on pretty  things. People  may have doubts about actions are flawless so they cannot be blamed some of their special attributes aee investing temperament, research and curiosity for anything that is now. In this progressive word something new is constantly happening. These naties are aware of this peep through every idea or thing. That is why there is orniginality in there thoughts and tgey hide the truth. Their actions are well planned and law abiding. They leave nothing poorly managed. They are able to guess what is going to happen in the future and act according generally their presumptions are corectThey are lucky chaps. Questions so change that roads automatically open out for them and they lead through the development and progress an a reach their desination. Their eaonomic side is Weak where others pass Over them. Nothing happens as per budget and money slips out of their hands As they are emotional and soft hearted, most of their time and money is spent up in charity. This is one reason for their weak financial status. They keep thinking. meditating in solitude. Their meeting with people is limited. Their friend circle is small and hardy any hobbies. They are happy with themselves. Their health is fine because they do not ignore it, living style is simple and they take balanced and normal diet. Areas of their interest are lectureship. witing, editing. heviewing and engineering. Tihey can make name in these felds. There is no blemish in their character nor are their thoughts defective. They JuSt cant harm others. If they can come out of their shel, become extrovert than the Society wil be benefited.")
  elif(dn==5):
    print("Attributes of Destiny No. 5 natives are activeness, alertness consciousness. They believe in removing all the faults of the system and amend them. They cannot sit at one place nor can they be natives in an unchanging dull environment. Their philosophy is that life: is the neme of onward march and it must keep changing- Their berhavior babuts thoughts also keep changing. Hence it is difficult to form a fixed opinion about them working under them are always scared as they dont know when and what will name them happy or angry. f they are happy with someone, then floodgate of favors will for him but if they are dispieased then they bring misery. In other words their future lije kings in some respects. Their own ideas, beliefs, likings and style of working are intangible. In this they do not want anybody's interference. They scoft at stuffy work abd schemes. Their canvas is wide. f there are plans thoy must be grand. But while  they start something with lot of publiaity and pomp, they things unfinished in a fit of pessimism and on kosing interest in t. Thus they do look at tge galf done work. Hence people do no trust them easily. They are fond of traveling  and hence like such jobs where the more opportunities of visiting places. They are real friends and can do anything for there friends. They can be successful agents  because they plan very well. Due to love of traveling they contact with new people. Hence they can succeed in agency assignments. There marriade life is not very satisfactory. Their hobby is To live glamorously in style. Costty clothes are their weakness surbed. Their habits adversely affect their budget disturbed. There habits adversely affect their married life.")
  elif(dn==6):
    print("This number represents devotion, dependable friends, and proficiency in thoughts,emitionaland understands  everything but people are under wrong impression that he does not know anything. He is well equipped to turn defeat into victory by one strock his move And then people are bewildered at his/her sharp wit. So no wonder if such natives are very successful in business and can be more successful if they work in Partnership somebody. Among friends they are very popular and know how to get brings to one. The only drawback in them is that they do not force their ideas on others. They consider themselves infalible and want everyone to follow their footsteps. When this does not happen situation of dispute is bound to arise. Because of their extravagant habit. they find themselves in financial problems and everyone including their family members, workers is compelled to suffer along with them. Financial situation worsens due to bad tnanagemen and situation normally goes so much out of control that it becomes virtually irreparable. They get support from friends, but are stabbed at the back by friends only. But this rarely happens. All things considered their situation with respect to friends is good. Destiny no. 6 persons can progress in the areas of jewelry, travel agency, health club, beauty,cosmeticarticles,interior decoration, theatre etc.They should pay attention to their financial aspect. Spend but keep in mind the income: Carelessness is dangerqus everywhere especially in the economic matters. It should not be ignored. They must take care of their health also.")
  elif(dn==7):
    print("Destiny No. 7 is symbolic of dare, devilry, courage, valour and hitting the bull's eye.The natives of this destiny number only know how to march ahead to achieve then goal.They  enjoy crossing all the hurdles and handicaps. Word impossible is stronger to them. Struggle is the destiny of their lives. They are satisfied only when they Attend their objectives. Steering through dificult situations, obstructions at every step and before them with tiheir mighty jaws open and these diehard people break them and least the flag the of success. They do not like any interference in their work plan and plan their work very systematically taking all things into consideration. They very well known that they will come across problems and so keep a margin for them. That is why they do not lose heart. They have fullest confidence in their abilities. Their will powers is stronge. There are no wrinkles on their forehead in adverse situation. They get hardened in tres  of problem and come out more able than before. The truth is only such people know how to live. Their health is good. Sometimes there may be minor abdominal disorders. They get no benefit from friends. On the contrary they help the friends in bad times. At the age of 28 their better time starts from the point of view of finances and by so they get settled down in their fields. hereafter, they go on consolidating their position.they can excel in fields of banking, farming, education, Yoga etc. They are curious people. They must not become moody of whimsical. it is necessary to interact with people. If they bear these things in mind, they will be more successful.")
  elif(dn==8):
    print("natives of destiny number 8 do not consider taking risks and endangering one's life foolishly. so long as they live, live happily is the keyword of their philosophy. They hesitate to put their friends in any type of serious work. It is not possible for them to hide any feeling or thought .They are like an open book. They are unable to digest any information and wait to renewal also someone as early as possible Hence they are unfit to work in a place where confidentiality Is required. These natives are foolish, self conceited and merry makers.Even is everything is lost they remain engrossed in their world of fun and frolic. They appear as if they are busiest people in the world. Snobbery is a big fault of these natives. They believe in short out: They drop mathematics like a hot brick. They do not participate in any debates or arguments. They do not worry about tomorrow i.e. they only live in the present. They do not save money nor do they try to make their future secure. If you have money todaý then eat, drink and be morry. They are lucky in the sense that they have large hearted fiends who help them from time to time. They are good looking. healthy and attractive. Carelessness is obvious in their style and ways. They are suitable for mining. insurance and public relation related functions. Only one advice that can be given to such natives is that they should not waste time in useless activities. there must be some seriousness in life.If they can control their habits then they can certainly register progress.")
  elif(dn==9):
    print("Will power of Destiny No. 9 natives is very strong. They are highly bad tempered. They start opposing anybody and create their enemies. But their great quality is high logical capacity. Whichever side they take whether it is right or wrong by their shan argument they silence their opponents. However, this quality becomes a vice when they start arguing on flimsy matters. These people are born in humble families but reach the top position on the strength of their abilities. They hate words like defeat, no etc. the continue to struggle till the objective is achieved. They find a route to their destination through obstacles and problems by hook or crook. They hardly get any help from family members or outsiders, but due to their faith in themselves and and unweaving to solve, they single handedly fight the adversities and have the last laugh. they relax only after attaining their aim. They are good at making friends. They improve that strangers with their sweet talking and make them do what they want to do. They get cooperations from friends and they find few friends everywhere. Officers of all departments  are their buddies. Thus the vehicle of their life keeps moving. Health wise they are fine but heart attack, blood pressure, blood disorders etc can not be rules out, Due to their explosive nature blood pressure is sure to go up. They can succeed in machinery industries ,management, research areas which are subjects of their interest. Due to strained relations between husband and wife married life is not too good. both walk in opposite directions and do not find way to understand each other. They are advises to check their anger.Whatever diffculties are in ,their lives is because hot of anger non-compromising nature. Hence if they only stop loosing their temper ,phone or other problems will automatically disappears. playing deliberately with dangers, displaying unrecalls for valor is neither wise nor proper. Hence they should adopt normal lif ike thers. When required their courage will come to your help. However peaple  of this destiny number are lucky.")
  else:
    print("invalid Input Kindly Check The Birthdate Again")

print("For What Do You Want Check Numerology:\n1.Name\n2.Company\n3.Both\n4.Destiny Number")
ask=input()
if(ask=='1' or ask=='name' or ask=='Name' or ask=='NAME'):
  name0()
elif(ask=='2' or ask=='Company' or ask=='company' or ask=='COMPANY'):
  comp0()
elif(ask=='3' or ask=='both' or ask=='Both' or ask=='BOTH'):
  both()
elif(ask=='4' or ask=='destiny number' or ask=='Destiny Number' or ask=='Destiny Number'):
  destiny()
else:
  print("Invalid Kindly Enter The Proper Input[1/2/3/4]")
