
import java.util.Scanner;


public class Main {
    public static void main(String[] args) {
        Scanner scan = new Scanner(System.in);
        String reset = "\u001B[0m";
        String red = "\u001B[31m";
        String green = "\u001B[32m";
        String yellow = "\u001B[33m";
        String blue = "\u001B[34m";
        String cyan = "\u001B[36m";
        String white = "\u001B[37m";
        String magenta = "\u001B[35m";
        String black = "\u001B[30m";
        String whiteBack = "\u001B[47m";
        String choice = "";
        String ready = "";
        int clan = 0;
        String action = "";
        String option = "";
        String secondOption = "";
        String thirdOption = "";
        String role = "";
        int ally = 0;
        String name = "";
        Clan clanAttributes = new Clan();
        while (!choice.equals("c")) {
            System.out.println();
            System.out.println("Welcome to ... " + white + "The Creator" + reset);
            System.out.println(" -----------");
            System.out.println("a. Create a new world");
            System.out.println("b. Info");
            System.out.println("c. quit");
            System.out.println("What would you like do you? (a/b/c)");
            choice = scan.nextLine();
            if (choice.equals("a")) {
                while (clan != 1 || clan != 2 || clan != 3 || clan != 4) {
                    System.out.println("1. " + red + "Vampire" + reset);
                    System.out.println("2. " + yellow + "Werewolf" + reset);
                    System.out.println("3. " + cyan + "Siren/Triton" + reset);
                    System.out.println("4. " + magenta + "Sorcerer" + reset);
                    System.out.println("randomizing clan....");
                    clan = Clan.randomizeClan(1, 4);
                    if (clan == 1) {
                        while (!(action.equals("run") || action.equals("follow") || action.equals("sleep"))) {
                            role = "vampire";
                            System.out.println("What's your name? ");
                            name = scan.nextLine();
                            System.out.println();
                            System.out.println();
                            System.out.println("Welcome to the " + red + role + " clan " + reset + name);
                            clanAttributes.vampirePicture();
                            System.out.println();
                            System.out.println();
                            System.out.println();
                            System.out.println("Your speech is in red and your allies are in their designated color.");
                            System.out.println("You awake in a dark forest...");
                            System.out.println("You see paw marks on the floor");
                            System.out.println("You have arrived in");
                            System.out.println();
                            System.out.println();
                            System.out.println();
                            clanAttributes.werewolfScenery();
                            System.out.println();
                            System.out.println();
                            System.out.println();
                            System.out.println(yellow + "WOLF TERRITORY" + reset);
                            System.out.println("You hear a low growl coming from a bush nearby...");
                            System.out.println("What do you do next? (run/ follow/ sleep");
                            action = scan.nextLine();
                            if (action.equals("run")) {
                                System.out.println();
                                System.out.println("By running you were mistaken for prey...");
                                System.out.println("You were chased and eaten alive");
                                System.out.println();
                                System.out.println(black + whiteBack + "YOU DIED :(" + reset);
                                System.out.println();
                                clanAttributes.endGame();
                                System.exit(0);
                            } else if (action.equals("follow")) {
                                while (!(option.equals("converse") || option.equals("attack"))) {
                                    System.out.println(yellow + "!!!" + reset);
                                    System.out.println("someone emerges from the bushes standing up from all fours.");
                                    System.out.println(yellow + "hello..." + reset);
                                    System.out.println("Do you converse or attack? ");
                                    option = scan.nextLine();
                                    if (option.equals("converse")) {
                                        while (!(secondOption.equals("attack") || secondOption.equals("converse") || secondOption.equals("run"))) {
                                            ally++;
                                            System.out.println("The werewolf admired your kindness...");
                                            System.out.println("You were introduced to the pack and have gained an ally");
                                            System.out.println("You have gained an ally!");
                                            System.out.println("You hear " + green + "humans " + reset + "coming and you and the others run until you wind up by the beach with your new ally");
                                            System.out.println("You see bodies of light circling you from within the water");
                                            System.out.println("You have arrived in");
                                            System.out.println();
                                            System.out.println();
                                            System.out.println();
                                            clanAttributes.sirenScenery();
                                            System.out.println();
                                            System.out.println();
                                            System.out.println();
                                            System.out.println(cyan + "SIREN TERRITORY" + reset);
                                            System.out.println("You see a gap in the circle around you for you to swim out ");
                                            System.out.println("What do you do next? (attack/ converse/ run");
                                            secondOption = scan.nextLine();
                                            if (secondOption.equals("attack")) {
                                                while (!(thirdOption.equals("attack") || thirdOption.equals("converse") || thirdOption.equals("run"))) {
                                                    System.out.println();
                                                    System.out.println("the sirens went straight into fight mode and attacked you.");
                                                    System.out.println("You were outnumbered... yet you still managed to escape by biting a sea creature with your fangs");
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    clanAttributes.vampireAttack();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println("You keep running till you end up near an abandoned tower");
                                                    System.out.println("You see flashing lights shining from within");
                                                    System.out.println("You have arrived in");
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    clanAttributes.sorcererScenery();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println(magenta + "SORCERER TERRITORY" + reset);
                                                    System.out.println("You have calmed down and the wolves have managed to escape with you.");
                                                    System.out.println("What do you do next? (run/ follow/ sleep");
                                                    thirdOption = scan.nextLine();
                                                    if (thirdOption.equals("run")) {
                                                        System.out.println("You run free but you do not have enough allies to save the world ;(");
                                                        clanAttributes.endGame();
                                                        System.exit(0);
                                                    } else if (thirdOption.equals("follow")) {
                                                        ally++;
                                                        System.out.println("The sorcerer greets everyone by the door.");
                                                        System.out.println("He shares his knowledge about the situation...");
                                                        System.out.println();
                                                        System.out.println(magenta + "as we know the humans are attempting to summon " + white + "The Creator" + magenta + " but they do not know once it arrives all life will be wiped...");
                                                        System.out.println("With my abilities I can help gather all the humans and tell them the truth to restore peace in the world!" + reset);
                                                        System.out.println(blue + "NEW ENDING UNLOCKED");
                                                        System.out.println("--------------------------------");
                                                        System.out.println("Not only did you save the world but you also saved humanity!");
                                                    } else if (thirdOption.equals("sleep")) {
                                                        System.out.println("You let your guard down and die");
                                                        System.out.println();
                                                        System.out.println(black + whiteBack + "YOU DIED :(" + reset);
                                                        System.out.println();
                                                        clanAttributes.endGame();
                                                        System.exit(0);
                                                    } else {
                                                        System.out.println();
                                                        System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                                        System.out.println();
                                                    }

                                                }
                                            } else if (secondOption.equals("converse")) {
                                                while (!(thirdOption.equals("attack") || thirdOption.equals("converse") || thirdOption.equals("run"))) {
                                                    System.out.println(red + "hello" + "  " + yellow + "is anyone there???" + reset);
                                                    System.out.println();
                                                    ally++;
                                                    System.out.println("For a while there was silence in the water until a a young sea creature came trying to make peace...");
                                                    System.out.println("The sirens were surprised at your attempt of trying to make peace");
                                                    System.out.println("You have gained an ally!");
                                                    System.out.println("You see " + green + "human" + reset + " sailors coming so you flee with your new allies");
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println("You keep running till you end up near an abandoned tower");
                                                    System.out.println("You see flashing lights shining from within");
                                                    System.out.println("You have arrived in");
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    clanAttributes.sorcererScenery();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println();
                                                    System.out.println(magenta + "SORCERER TERRITORY" + reset);
                                                    System.out.println("You have calmed down and the others have escaped with you.");
                                                    System.out.println("What do you do next? (run/ follow/ sleep");
                                                    thirdOption = scan.nextLine();
                                                    if (thirdOption.equals("run")) {
                                                        System.out.println("You run free and as you have enough support you are able to fight the humans and save the world!");
                                                        clanAttributes.endGame();
                                                        System.exit(0);
                                                    } else if (thirdOption.equals("follow")) {
                                                        ally++;
                                                        System.out.println("The sorcerer greets everyone by the door.");
                                                        System.out.println("He shares his knowledge about the situation...");
                                                        System.out.println();
                                                        System.out.println(magenta + "as we know the humans are attempting to summon " + white + "The Creator" + magenta + " but they do not know once it arrives all life will be wiped...");
                                                        System.out.println("With my abilities I can help gather all the humans and tell them the truth to restore peace in the world!" + reset);
                                                        System.out.println(blue + "NEW ENDING UNLOCKED");
                                                        System.out.println("--------------------------------");
                                                        System.out.println("Not only did you save the world but you also saved humanity!");
                                                    } else if (thirdOption.equals("sleep")) {
                                                        System.out.println("You let your guard down and die");
                                                        clanAttributes.endGame();
                                                        System.exit(0);
                                                    } else {
                                                        System.out.println();
                                                        System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                                        System.out.println();
                                                    }

                                                }

                                            } else if (secondOption.equals("run")) {
                                                System.out.println();
                                                System.out.println("You cannot run when you're in water and the sirens drag you down");
                                                clanAttributes.endGame();
                                                System.exit(0);
                                            } else {
                                                System.out.println();
                                                System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                                System.out.println();
                                            }
                                        }
                                    } else if (option.equals("attack")) {
                                        System.out.println();
                                        clanAttributes.endGame();
                                        System.exit(0);
                                    }
                                }
                            } else if (action.equals("sleep")) {
                                System.out.println();
                                System.out.println("By sleeping you let your guard down");
                                System.out.println("They inspected that you were a vampire and sent a dagger through you as you were sleeping.");
                                System.out.println();
                                System.out.println(black + whiteBack + "YOU DIED :(" + reset);
                                System.out.println();
                                clanAttributes.endGame();
                                System.exit(0);
                            } else {
                                System.out.println();
                                System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                System.out.println();
                            }
                        }
                    } else if (clan == 2) {
                        while (!(action.equals("attack") || action.equals("converse") || action.equals("run"))) {
                            role = "werewolf";
                            System.out.println("What's your name? ");
                            name = scan.nextLine();
                            System.out.println();
                            System.out.println();
                            System.out.println("Welcome to the " + yellow + role + " clan " + reset + name);
                            clanAttributes.werewolfPicture();
                            System.out.println();
                            System.out.println();
                            System.out.println();
                            System.out.println("You awake from a shipwreck on a secluded island");
                            System.out.println("You see bodies of light circling you from within the water");
                            System.out.println("You have arrived in");
                            System.out.println();
                            System.out.println();
                            System.out.println();
                            clanAttributes.sirenScenery();
                            System.out.println();
                            System.out.println();
                            System.out.println();
                            System.out.println(cyan + "SIREN TERRITORY" + reset);
                            System.out.println("You see a gap in the circle around you for you to swim out ");
                            System.out.println("What do you do next? (attack/ converse/ run");
                            action = scan.nextLine();
                            if (action.equals("attack")) {
                                System.out.println();
                                System.out.println("the sirens went straight into fight mode and attacked you.");
                                System.out.println("You were outnumbered... the sea creatures drowned you!");
                                clanAttributes.endGame();
                                System.exit(0);


                            } else if (action.equals("converse")) {
                                while (!(option.equals("run") || option.equals("follow") || option.equals("sleep"))) {
                                    System.out.println(red + "hello" + "  " + yellow + "is anyone there???" + reset);
                                    System.out.println();
                                    ally++;
                                    System.out.println("For a while there was silence in the water until a a young sea creature came trying to make peace...");
                                    System.out.println("The sirens were surprised at your attempt of trying to make peace");
                                    System.out.println("You have gained an ally!");
                                    System.out.println("You see " + green + "human" + reset + " sailors coming so you flee with your new allies");
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println("You flee with your ally until you reach in front of a dark secluded castle");
                                    System.out.println("You hear a piano coming from within");
                                    System.out.println("You have arrived in");
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    clanAttributes.vampireScenery();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println(red + "VAMPIRE TERRITORY" + reset);
                                    System.out.println("You see the front door crack open ");
                                    System.out.println("What do you do next? (run/ follow/ sleep");
                                    option = scan.nextLine();
                                    if (option.equals("run")) {
                                        System.out.println("You were hunted down and ");
                                    } else if (option.equals("sleep")) {
                                        System.out.println();
                                        System.out.println("The vampires kidnapped you!");
                                        System.out.println("You were outnumbered... yet you still managed to escape by scratching a vampire with your claws");
                                        System.out.println();
                                        System.out.println();
                                        System.out.println();
                                        System.out.println();
                                        clanAttributes.werewolfAttack();
                                        System.out.println();
                                        System.out.println();
                                        System.out.println();
                                        System.out.println("You keep running till you end up near an abandoned tower");
                                        System.out.println("You see flashing lights shining from within");
                                        System.out.println("You have arrived in");
                                        System.out.println();
                                        System.out.println();
                                        System.out.println();
                                        clanAttributes.sorcererScenery();
                                        System.out.println();
                                        System.out.println();
                                        System.out.println();
                                        System.out.println(magenta + "SORCERER TERRITORY" + reset);
                                        System.out.println("You have returned back to human form");
                                        System.out.println("What do you do next? (run/ follow/ sleep");
                                        secondOption = scan.nextLine();
                                    } else if (option.equals("follow")) {
                                        while (!(secondOption.equals("converse") || secondOption.equals("attack"))) {
                                            System.out.println(red + "!!!" + reset);
                                            System.out.println("someone emerges from the darkness of the halls");
                                            System.out.println(red + "hello..." + reset);
                                            System.out.println("Do you converse or attack? ");
                                            secondOption = scan.nextLine();
                                            if (secondOption.equals("converse")) ;
                                            System.out.println();
                                            ally++;
                                            System.out.println("The vampires were happy to become allies in this desperate time.");
                                            System.out.println("You have gained a new ally");
                                            System.out.println();
                                            System.out.println("You start to hear a hoard of humans with pitchforks rallying in front the castle");
                                            System.out.println("You and your new allies escape");
                                            System.out.println("You keep running till you end up near an abandoned tower");
                                            System.out.println("You see flashing lights shining from within");
                                            System.out.println("You have arrived in");
                                            System.out.println();
                                            System.out.println();
                                            System.out.println();
                                            clanAttributes.sorcererScenery();
                                            System.out.println();
                                            System.out.println();
                                            System.out.println();
                                            System.out.println(magenta + "SORCERER TERRITORY" + reset);
                                            System.out.println("You and your new allies have calmed down");
                                            System.out.println("What do you do next? (run/ follow/ sleep");
                                            if (thirdOption.equals("run")) {
                                                System.out.println("You run free and as you have enough support you are able to fight the humans and save the world!");
                                                System.exit(0);
                                            } else if (thirdOption.equals("follow")) {
                                                ally++;
                                                System.out.println("The sorcerer greets everyone by the door.");
                                                System.out.println("He shares his knowledge about the situation...");
                                                System.out.println();
                                                System.out.println(magenta + "as we know the humans are attempting to summon " + white + "The Creator" + magenta + " but they do not know once it arrives all life will be wiped...");
                                                System.out.println("With my abilities I can help gather all the humans and tell them the truth to restore peace in the world!" + reset);
                                                System.out.println(blue + "NEW ENDING UNLOCKED");
                                                System.out.println("--------------------------------");
                                                System.out.println("Not only did you save the world but you also saved humanity!");
                                            }
                                        }


                                    } else if (action.equals("run")) {
                                        System.out.println();
                                        System.out.println("You cannot run when you're in water and the sirens drag you down");
                                        clanAttributes.endGame();
                                        System.exit(0);
                                    } else {
                                        System.out.println();
                                        System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                        System.out.println();
                                    }
                                }

                            } else if (clan == 3) {
                                while (!(action.equals("run") || action.equals("follow") || action.equals("sleep"))) {
                                    System.out.println("What's your name? ");
                                    name = scan.nextLine();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println("Welcome to the " + cyan + role + " clan " + reset + name);
                                    clanAttributes.sirenPicture();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println("You awake washed up near an abandoned tower");
                                    System.out.println("You see flashing lights shining from within");
                                    System.out.println("You have arrived in");
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    clanAttributes.sorcererScenery();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println(magenta + "SORCERER TERRITORY" + reset);
                                    System.out.println("You have returned back into your human form");
                                    System.out.println("What do you do next? (run/ follow/ sleep");
                                    action = scan.nextLine();


                                }


                            } else if (clan == 4) {
                                while (!(action.equals("run") || action.equals("follow") || action.equals("sleep"))) {
                                    System.out.println("What's your name? ");
                                    name = scan.nextLine();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println("Welcome to the " + magenta + role + " clan " + reset + name);
                                    clanAttributes.sorcererPicture();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println("You awake in front of a dark secluded castle");
                                    System.out.println("You hear a piano coming from within");
                                    System.out.println("You have arrived in");
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    clanAttributes.vampireScenery();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println();
                                    System.out.println(red + "VAMPIRE TERRITORY" + reset);
                                    System.out.println("You see the front door crack open ");
                                    System.out.println("What do you do next? (run/ follow/ sleep");
                                    action = scan.nextLine();


                                }


                            } else {
                                System.out.println();
                                System.out.println();
                                System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                System.out.println();
                                System.out.println();


                            }
                        }
                    } else if (choice.equals("b")) {
                        while (!(ready.equals("ready"))) {
                            System.out.println(blue + "OBJECTIVE" + reset);
                            System.out.println(white + "---------" + reset);
                            System.out.println("Get all of the clans together to fight against the humans and the evil they summon");
                            System.out.println("You will have ally points and keeping track of how many allies you've gained.");
                            System.out.println("Depending on what clan you choose to be in you will have either energy points or health points");
                            System.out.println();
                            System.out.println("Type \"ready\" when ready to go back to main menu");
                            ready = scan.nextLine();
                            if (ready.equals("ready")) {


                            } else {
                                System.out.println();
                                System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                                System.out.println();
                            }
                        }

                    } else if (choice.equals("c")) {
                        System.exit(0);
                    } else {
                        System.out.println();
                        System.out.println();
                        System.out.println(black + whiteBack + "Please type a valid choice" + reset);
                        System.out.println();
                        System.out.println();


                    }
                }
            }
        }
    }
}
