# game.py
#!/bin/python

import os,sys,time
def bersih():
    os.system("clear")

def menu():
    bersih()
    print "|\033[97m---------------------------------------\033[97m|"
    print "|\033[92mAuthor    : \033[96mHapid H.R.D.C.R            \033[97m|"
    print "|\033[92mGroup     : \033[96mCyber hrdcr                \033[97m|" 
    print "|\033[92mInstagram : \033[96mHapid hrdcr                \033[97m|"
    print "|\033[92mGithub    : \033[96mhttps://github.com/HRDCR-ID\033[97m|"
    print "|       \033[97mGame Di Terminal Termux         |"
    print "|\033[97m---------------------------------------\033[97m|"
    print "|1] .Cmatrix                            |"
    print "|2] .nsnake                             |"
    print "|3] .moon-buggy                         |"
    print "|4] .bastet                             |"
    print "|5] .Ttysolitaire                       |"
    print "|6] .Curseofwar                         |"
    print "|7] .gnugo                              |"
    print "|8] .greed                              |"
    print "|9] .nudoku                             |"
    print "|10].Nethack                            |"
    print "|00].Keluar/Exit                        |"
    print "\033[97m|_______________________________________|"
    pil = raw_input("|Pilih Gamenyah Silahkan =>* ")
    if pil == "1":
        os.system("pkg install cmatrix")
        os.system("cmatrix")
    elif pil == "2":
        os.system("pkg install nsnake")
        os.system("nsnake")
    elif pil == "3":
        os.system("pkg install moon-buggy")
        os.system("moon-buggy")
    elif pil == "4":
        os.system("pkg install bastet")
        os.system("bastet")
    elif pil == "5":
        os.system("pkg install tt-ysolitaire")
        os.system("ttysolitaire")
    elif pil == "6":
        os.system("pkg install curseofwar")
        os.system("curseofwar")
    elif pil == "7":
        os.system("pkg install gnugo")
        os.system("gnugo")
    elif pil == "8":
        os.system("pkg install greed")
        os.system("greed")
    elif pil == "9":
        os.system("pkg install nudoku")
        os.system("nudoku")
    elif pil == "10":
        os.system("pkg install nethack")
        os.system("nethack")
    elif pil == "00":
        os.system("clear")
        sys.exit()
    else:
        print "INPUT SALAH"
        time.sleep(2)
        os.system("python2 Game.py")
menu()
