# Red Stains & Gold Eyes
import time
import sys

sanity = 100
found_funds = False

def slow_print(text, delay=0.001, wait_for_input=True):
    for char in text:
        sys.stdout.write(char)
        sys.stdout.flush()
        time.sleep(delay)
    print()

def pause(seconds=1.5):
    time.sleep(seconds)

def change_sanity(amount):
    global sanity
    sanity += amount
    sanity = max(0, min(100, sanity))

def intro():
    slow_print("Red Stains & Gold Eyes")
    slow_print("A tragedy wrapped in vibrant reds and Shakespearean plays. Inspired by the song \"Maroon\" by Taylor Swift.")
    pause(2)

def wine_spill_scene():
    slow_print("You never wanted to kill him.") 
    slow_print("You remember him. The air smelt of cheap incense and theater dust.") 
    slow_print("Robbie spins in the living room, still in costume, wearing gold eyeliner that catches the warm kitchen light.") 
    slow_print("He twirls a wine glass, trips over a throw pillow, and crashes to the hardwood.")
    pause()
    slow_print("The rosé flies—dark, staining, like a wound—across your burgundy shirt.")  
    slow_print("You gasp. His laugh bubbles up like a musical cue.")  
    slow_print("Both of you helplessly collapse into the ground, giggling until you can't breathe properly.")  
    slow_print("Lying on the floor, inches apart, his perfect gold eyeliner glints brightly.") 
    slow_print("After the play, he told you he wore it because he wanted to look like Cinna from the Hunger Games.") 
    slow_print("He catches you staring.\"New thing I’m trying out. Does it look good on me, Scarlett?\"")
    print("\nHow do you respond?")
    print("1. It's the stupidest thing I've ever seen. So ugly.")
    print("2. Yeah, it really suits you!")
    print("3. You look beautiful.")
    choice = input("> ").strip()
    if choice == "1":
        slow_print("\"It's the stupidest thing I've ever seen. So ugly.\" You tell him. He laughs. \"Geez, you didn't pull back any punches, huh?\"")
        change_sanity(-2)
    elif choice == "2":
        slow_print("\"Thanks, love.\" Your heart flutters.")
        change_sanity(+2)
    elif choice == "3":
        slow_print("He smiles. \"Not much as you though.\"")
        change_sanity(+5)
    else:
        slow_print("He blinks at you, confused. \"Was that a yes or a no?\"")
        change_sanity(-1)
    pause()
    slow_print("He looks around the apartment.")
    slow_print("\"How'd we end up on the floor anyway?\" Robbie asks you breathlessly.") 
    slow_print("\"Your roommate’s cheap-ass screw-top rosé, that’s how.\" You shoot back.")  
    slow_print("You both collapse in laughter. That dirty t-shirt will never be the same.")  
    pause()
    slow_print("You’ll keep it anyway.") 
    change_sanity(-5)

def flashback():
    slow_print("\n—Flashback—")
    slow_print("New York at 2AM. Robbie dances in the streetlight puddles like he’s auditioning for God.") 
    slow_print("You’re pulled along, laced fingers, as he quotes something Shakespearean under his breath.") 
    slow_print("Robbie: \"I'm telling you, I was born to dance under the Times Square billboards!\" he yells to you gleefully.") 
    slow_print("You laugh as you study him. You, the hardworking, steadfast comp sci major.") 
    slow_print("Him, the theater nerd that thinks he'll make it to Broadway.") 
    slow_print("You hate to code, but...it's stable. Reliable. A promising future, even if you loathe it.") 
    slow_print("But Robbie? He's a true New York dreamer. All open flame and delusion. Theatrics and melodrama.") 
    pause()
    slow_print("You can't imagine having that much passion.") 
    slow_print("He continues his dancing in the Times Square lights. People stare, but he doesn't seem to care.")

    print("\nHow do you respond?")
    print("1. What are you doing?")
    print("2. You're embarrassing yourself.")
    print("3. People are staring, my guy.")
    print("4. (Say nothing)")

    choice = input("> ").strip()

    if choice == "1":
        slow_print("He grins. \"Whatever I want!\"")
        change_sanity(+2)
    elif choice == "2":
        slow_print("\"At least I'm not being boring like you, Mrs. Grinch!\" He laughs.")
        change_sanity(-2)
    elif choice == "3":
        slow_print("\"Who cares?\" he yells with glee. \"As Shakespeare once said, 'All the world's a stage!'\"")
        change_sanity(+1)
    elif choice == "4":
        slow_print("Robbie waves his arms and does a silly dance to make you laugh. It works.")
        change_sanity(+1)
    else:
        slow_print("Robbie cocks his head. \"That wasn't one of the options, genius.\"")
        change_sanity(-1)

    pause()
    slow_print("You sigh as you watch him finish his crazy performance.")
    slow_print("You envy him. Maybe even love him.")

def fund_puzzle():
    global found_funds
    slow_print("\nYou step into the apartment. The water comes up to your knees. The radiator screams.")
    slow_print("You panic. Not because the flood destroyed your and Robbie's apartment.")
    slow_print("But because you don't have the money to fix it.")
    slow_print("Your heartbeat quickens. Your palms sweat. The repair bills will crush you.")
    slow_print("All those dreams of a stable life...")
    pause()
    slow_print("Gone.") 
    pause()
    slow_print("You know where Robbie hides things — he’s careless that way. He trusts too easily.")
    slow_print("You need money to fix the apartment. His funds for acting school... it’s somewhere.")
    attempts = 0
    while not found_funds:
        slow_print("\nWhere will you look?")
        slow_print("1. Under Robbie's mattress")
        slow_print("2. Inside his folder of audition scripts")
        slow_print("3. In the dusty teapot on the shelf")
        slow_print("4. Behind the giant WICKED poster")
        choice = input("> ")
        attempts += 1
        if choice == "3":
            found_funds = True
            slow_print("The teapot rattles with hidden weight. Inside: an envelope, labeled 'Broadway, here I come!'.")
            slow_print("You hold the cash and whisper an apology he’ll never hear. Not really.")
        else:
            slow_print("Empty. Dust. Nada. Try again.")
            change_sanity(-5)
            if attempts > 4:
                slow_print("You feel watched. The apartment is still, but somehow hostile.")

def argument_scene():
    global sanity
    slow_print("\nHe finds out.")
    slow_print("Robbie: \"You took it? You actually—you used the money?!\"")
    slow_print("His eyes glisten with tears. That same gold eyeliner, now a mockery.")
    slow_print("Choose your reply:")
    slow_print("1. \"I did what I had to. You’d never have made it.\"")
    slow_print("2. \"I needed it. Our apartment was drowning, Robbie!\"")
    slow_print("3. \"You and your stupid dreams. I'm tired of this nonsense.\"")
    choice = input("> ")
    if choice == "1":
        slow_print("He goes still. The hurt sinks deep.")
        slow_print("Robbie: \"I guess I never knew you at all, Scarlett.\"")
        change_sanity(-25)
    elif choice == "2":
        slow_print("He shakes his head in disbelief. \"So you just decided my dream was worthless?\"")
        change_sanity(-15)
    elif choice == "3":
        slow_print("He screams. Quoting Shakespeare. Crying like his heart’s been pierced.")
        slow_print("You feel nothing. Or maybe too much.")
        change_sanity(-35)
    else:
        slow_print("You say nothing. The silence crushes him.")
        change_sanity(-20)

def murder_scene():
    slow_print("\nTHE PUSH:")
    slow_print("Both of you exit the apartment in a rushed fury.")
    slow_print("The metal stairwell echoes with both your screams. Gold eyeliner streaks. Your anger spills raw.")
    slow_print("But when Robbie is shouting at you, there is more sadness than anger in his eyes.")
    slow_print("He looks exactly like he did a year ago, on your birthday.")
    slow_print("\"I can't believe I messed up so badly,\" he said back then with a sigh.")
    slow_print("As a gift, he bought you carnations instead of roses.")
    print("\nWhat do you say to him?")
    print("1. It's alright, things happen.")
    print("2. Bad mistake, man. I guess I could buy more flowers?")
    print("3. At least they'll still look pretty on the windowsill!")
    if choice == "1":
        slow_print("\nHe forces a smile that doesn't make you feel quite nice.")
    elif choice == "2":
        slow_print("\nHis head drops in shame. You change the topic, as you regret making him feel bad with a single comment.")
    elif choice == "3":
        slow_print("\nHe laughs. You can still see the guilt in his face as you laugh with him. You hope that he'll forget about it like he always does.")
    else:
        slow_print("\nHe says nothing, confused by your silence. Maybe you were both just tired that day.")

    slow_print("\nBut you remember the guilt and sorrow in his gold-lined eyes.")
    slow_print("It mirrors the eyes you see right now.")

    pause()
    slow_print("Anger flashes through your head. So do your memories.")
    slow_print("Dancing in NYC streets. Cafe dates and junk food. Hour-long calls on rusty landlines.") #dancing silhouette
    slow_print("You did it to save him! To save the apartment you both shared!") #cash envelope
    slow_print("He wouldn't ever succeed anyway, deluded by an impossible dream.") # broadway
    slow_print("How could he not understand?") # small red circile
    slow_print("How could he act like this to you?") # medium red circle on top of the other one
    slow_print("How could he stand there, throwing a fit like an angry child?") # larger circle on top
    pause()
    slow_print("You realize that you hate him.") #knife in an open hand
    pause()
    slow_print("You realize that you want him gone.") #fingers close around the knife and grip it
    pause()
    slow_print("He turns to leave. You shove.") #black silhouette on red screen
    pause()
    slow_print("A sickening crack. The blood spreads like spilled paint. Maroon.")
    slow_print("His eyeliner smears like a final curtain call.")
    change_sanity(-40)
    slow_print("The neighbor, an old lady, opens her door. You sob. You act.")

    print("\nWhat do you say to the neighbor?")
    print("1. \"Please, I need your help. It's serious.\"")
    print("2. \"Call an ambulance. Now.\"")
    print("3. \"I—I think he's dying.\"")
    print("4. Say nothing. Just sob.")

    choice = input("> ").strip()

    if choice == "1":
        slow_print("Your voice cracks. \"Please, I need your help. It's serious.\"")
        slow_print("She fumbles for her phone, nodding quickly.")
    elif choice == "2":
        slow_print("You yell the order: \"Call an ambulance. Now.\"")
        slow_print("Startled, she stares for half a second, and then dials with shaking fingers.")
    elif choice == "3":
        slow_print("You clutch at her sleeve. \"I—I think he's dying.\"")
        slow_print("Her face drains of color. She pulls out her phone immediately and dials 9-1-1.")
    elif choice == "4":
        slow_print("You say nothing. Just sob—loud, messy, uncontrollable.")
        slow_print("She takes one look at you, and starts dialing 9-1-1 without a word.")
    else:
        slow_print("You stammer something incoherent.")
        slow_print("She doesn't wait for clarity. She calls 9-1-1 anyway.")

    pause()
    slow_print("Somewhere in your head, a voice whispers: \"What a performance. Maybe I'm the one who should have been an actor.\"")
    slow_print("The voice in your head cackles maniacally.") # evil green goblin thing cackles with a wicked grin
    slow_print("But the guilt forms a pit in your stomach.") # sad??
    pause(2)
    print(" - ")
    slow_print("The building is a blur of uniforms and voices.")
    slow_print("Someone asks you questions you don't remember. Someone pats your arm as a condolence.")
    slow_print("But you only remember two things:")
    pause()
    slow_print("Robbie's hollow-eyed body being zipped away in a body bag.")
    pause(2)
    slow_print("And the maroon.")
    slow_print("That beautiful, vibrant color. You see it everywhere.")
    slow_print("In the siren's glow. In the red of the ambulance.")
    slow_print("Even the sunset seemed to taunt you with that stunning red.")
    pause()
    slow_print("You smile.")
    slow_print("You remember that line Robbie always says. The voice in your head recites it perfectly.")
    slow_print("\"The evil that men do lives after them; the good is oft interred with their bones.\"")
    slow_print("You laugh under your breath.") # cheshire grin
    pause()
    slow_print("The voice sounded exactly like him.")

def haunting():
    slow_print("\nAFTERMATH:")
    if sanity <= 50:
        slow_print("You hear him. Robbie. Reciting snarky lines only you can hear.")
        slow_print("\"What a shame, Scarlett. Hurts almost as much as when you killed me.\"")
        change_sanity(-10)
    if sanity <= 20:
        slow_print("Mirrors show flashes of gold eyes and crimson stains. You smile back at the ghost.")
        slow_print("He follows you day by day. Making snide comments and dishing out lines from his favorite plays.")
        slow_print("You feel comforted. He never left you. He never will.") # you silhouette and ghost robbie behind you

def new_alley_ending():
    slow_print("\nENDING — THE ALLEY:")
    slow_print("Rockefeller Center. A girl in a maroon shirt skates with glee.")
    slow_print("You ball your fists and clench your teeth.")
    slow_print("Faint memories of wine and stained t-shirts arise. Fits of laughter on hardwood floors.")
    slow_print("She wears your color. Robbie's color.")
    pause()
    slow_print("How dare she think she can act just like him.") # black words on red screen
    slow_print("Robbie's ghost smiles tauntingly. \"In my opinion, you should give her a piece of your mind.\"") 
    slow_print("You follow her. Past the rink. Past the lights. Past the laughter.") 
    pause(1)
    slow_print("Into a dark alley, quiet and slick with recent rain.")
    slow_print("She turns. \"Can I help—\"")
    pause(1)
    slow_print("A scream. Your knife. Then nothing but silence.")
    slow_print("You crouch beside her body. The blood pools. Deep. Dark. Beautiful. Maroon.")
    slow_print("You touch it with reverence.")
    pause()

    while True:
        print("\nWhat do you say to the empty alley?")
        print("1. \"Robbie, you’d love this stage lighting.\"")
        print("2. \"Look, love, I found our color.\"")
        print("3. \"It always comes back to maroon, doesn’t it?\"")
        choice = input("> ").strip()

        if choice == "1":
            slow_print("You: \"Robbie, you’d love this stage lighting.\"")
            slow_print("In the corner of your eye, you see him. Blood-stained and golden-eyed.")
            slow_print("His gold lined eyes scan the scene.")
            slow_print("He smiles. \"It's beautiful, Scarlett.\"")
            break
        elif choice == "2":
            slow_print("You: \"Look, love, I found our color.\"")
            slow_print("In the corner of your eye, you see him smile. Blood-stained and beautiful.")
            break
        elif choice == "3":
            slow_print("You: \"It always comes back to maroon, doesn’t it?\"")
            slow_print("In the corner of your eye, you see Robbie grin. Blood-stained, golden-eyed, and beautiful.")
            slow_print("\"Of course it does, that's your signature color.\" He teases.")
            break
        else:
            slow_print("You say nothing. You look to the sky.")
            slow_print("It's a deep red. Sunset maroon.")
            pause()
            slow_print("A truly perfect evening.")
            break

    pause()
    slow_print("Sirens rise in the distance. Someone shouts. Muffled footsteps creep closer, approaching your direction.")
    slow_print("You don’t run.")
    pause(2)
    slow_print("They find you kneeling in the blood, laughing like you’ve finally made it to Broadway.")
    slow_print("Robbie is right there, laughing with you.")
    slow_print("He whispers in your ear \"All the world's a stage... and you? You're the finale.\"")
    slow_print("\n— THE END —")


def play_game():
    intro()
    wine_spill_scene()
    pause()
    flashback()
    pause()
    fund_puzzle()
    pause()
    argument_scene()
    pause()
    murder_scene()
    pause()
    haunting()
    pause()
    new_alley_ending()

if __name__ == "__main__":
    play_game()
