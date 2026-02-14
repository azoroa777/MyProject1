# My Code 

## MyCode 1

#include <iostream>

using namespace std ;

enum enName { Ali, Ahmed, Sarah, John, Maria} ;
enum enVerb {Run, Eat, Jump, Sleep, Write} ;
enum enAdjective {Happy, Sad, Tall, Short, Fast};
enum enTotal {Name , Verb , Adjective};

struct Word 
{
    enName Names ;
    enVerb Verbs ;
    enAdjective Adjectives ;
    int num1 ;
    int num2 ;
    string TryAgine ;

};

int main()
{
    Word Words ;
    
    do 
    {
        cout << "Choses what you want :- \n0 - Name \n1 - Verb \n2 - Adjective \n===> ";
        cin >> Words.num1 ;
    
        if (Words.num1 == 0)
        {
            cout << "chose your name : \n0 - Ali \n1 - Ahmed \n2 - Sarah \n3 - John \n4 - Maria \n===> ";
            cin >> Words.num2 ;
    
            switch(Words.num2)
            {
                case Ali : cout << "Your Name is : Ali " << endl  ; break;
                case Ahmed : cout << "Your Name is : Ahmed " << endl ; break;
                case Sarah : cout << "Your Name is : Sarah " << endl  ; break;
                case John : cout << "Your Name is : John " << endl  ; break;
                case Maria : cout << "Your Name is : Maria " << endl ; break; 
                default : cout << "Type Error" ; break;
            }
                
        }
        else if (Words.num1 == 1)
        {
            cout << "chose you name : \n0 - Run \n1 - Eat \n2 - Jump \n3 - Sleep \n4 - Write \n===> ";
            cin >> Words.num2 ;
    
            switch(Words.num2)
            {
                case Run : cout << "Your Verb is : Run " << endl ; break;
                case Eat : cout << "Your Verb is : Eat " << endl  ; break;
                case Jump : cout << "Your Verb is : Jump " << endl ; break;
                case Sleep : cout << "Your Verb is : Sleep " << endl  ; break;
                case Write : cout << "Your Verb is : Write " << endl  ; break; 
                default : cout << "Type Error" ; break;
            }
                
        }
        else if (Words.num1 == 2)
        {
            cout << "chose you name : \n0 - Happy \n1 - Sad \n2 - Tall \n3 - Short \n4 - Fast \n===> ";
            cin >> Words.num2 ;
    
            switch(Words.num2)
            {
                case Happy : cout << "Your Adjective is : Happy " << endl ; break;
                case Sad : cout << "Your Adjective is : Sad " << endl ; break;
                case Tall : cout << "Your Adjective is : Tall " << endl  ; break;
                case Short : cout << "Your Adjective is : Short " << endl ; break;
                case Fast : cout << "Your Adjective is : Fast " << endl ; break; 
                default : cout << "Type Error" ; break;
            }
                
        }

        cout <<"Do you want to try agine ? [yes / no] : " ;
        cin >> Words.TryAgine ;
    }while (Words.TryAgine == "yes");
    
}

## Projecte note
