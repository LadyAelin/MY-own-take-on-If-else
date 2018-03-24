# MY-own-take-on-If-else
#include <stdio.h>
#include <stdlib.h>

//My own take on if else

int main()
{
    int choice;

    printf("On a scale of 1 to 10, how likely are you to follow your dreams?\n");
    scanf("%d", &choice);

    if (choice >= 8)
    {
        printf("Then what are you waiting for?!\n");
        printf("Get out there. I'll be rooting for you\n");
    }

    else if (choice >= 5)

    {
        printf("Ok very fair\n");
        printf("OMG life is real eh?\n");
    }

    else if (choice >=3)
    {
        printf("I'm guessing circumstances are making it hard huh\n");
        printf("Don't give up on your dreams yet!\n");
    }

    else

    {
        printf("I'm guessing you are a hard realist\n");
        printf("more power to ya!\n");
    }

    int comfort;
    printf("\nOn a Scale of 1 to 10, how comfortable are you with yourself?\n");
    scanf("%d", &comfort);

    if (comfort >= 8)
    {
        printf("Ayyy friskayy\n");
    }

    else if (comfort >= 5)
    {
        printf("Not bad at all\n");
        printf("Keep at it and you'll get even better!\n");
    }

    else if (comfort >= 3)
    {
        printf("Awww perhaps there is something you can do to feel comfortable!\n");
        printf("Cheer up ma bruh\n");
    }

    else
    {
        printf("There is always hope\n");
        printf("Please hold on to it. You are as brilliant as the sun. Don't forget it\n");
    }


    int happiness;
    printf("\nOn a scale of 1-10, how happy are you with the world?\n");
    scanf("%d", &happiness);

    if (happiness >=8)
    {
        printf("Danngggg I see you. Life been gooooddd");
        printf("Positive mindsets go a long way!");
    }

    else if (happiness >= 5)
    {
        printf("Hmm so moderate, but I see you know about the world a bit\n");
        printf("The world is so a ok\n");
    }

    else if (happiness >= 3)
    {
        printf("You must be fun at parties\n");
        printf("Such a realist!\n");
    }

    else
    {
        printf("Duddeeeee talk to me although I am a program\n");
        printf("Wanna go out for some drinks sometime?\n");
    }











    return 0;
}
