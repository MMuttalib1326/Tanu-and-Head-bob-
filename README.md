# Tanu-and-Head-bob-
Tanu has got interested in signs and gestures that we use for communication. One such gesture is the head-bob. When we want to signal "Yes" to someone, we move the head up-and-down. For "No", the head is moved left-and-right, rotating about the vertical axis. There is a peculiar way of gesturing "Yes", commonly seen in India, by moving head sideways (rotating about the forward-back axis). This is called the Indian head-bob.  Tanu observed many people on the railways station, and made a list of gestures that they made. Usual "Yes" gesture is recorded as "Y", no as "N" and Indian "Yes" gesture as "I". (Assume no foreigner uses the Indian "Yes" gesture and vice-versa). Identify which of them were Indians, which were not Indian, and which one you cannot be sure about.


n=int(input())
for i in range(n):
    M=int(input())
    L=input()
    if 'Y' in L:
        print("NOT INDIAN")
    elif 'I' in L:
        print("INDIAN")
    else:
        print("NOT SURE")
