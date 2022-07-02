
- 👋 Hi, I’m @vedantkavhar
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
vedantkavhar/vedantkavhar is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
#include <stdio.h>
int main() 
{
    int age ,n;
     
   printf("Enter your age:");
   scanf("%d",&age);
   printf("Your age :%d\n",age);
   
   if(age>30 && age<60)
   {
     printf("This guidance is not for you");
   }
   else
   {
     printf("Which disease are you suffering from?\n");
     printf("1:skin cancer\n");
     printf("2:diabetes\n");
     printf("3:asthma\n");
     printf("4:respiratory disease\n");
     printf("5:Depression\n");
     printf("6:liver disease\n");
     printf("7:Influenza \n");
     printf("8:pneumonia\n");
     printf("9:Acne\n");
     printf("10:hair loss\n");
     printf("11:physical illness\n");
     printf("12:blood pressure\n");
     printf("13:heart disease\n");
     printf("14:alcohol detox\n");
     printf("15:anxiety\n");
     
    
     scanf("%d",&n);
   }
   printf("you should follow following diet plan to cure the disease\n");
   switch(n)
   {
    case 1:
    {
      printf("(1))orange-colored vegetables and fruits,       including carrots, squash, sweet potatoes, cantaloupe, apricots and mangoes.\n(2) tomatoes, watermelon, guava, papaya, apricots, pink grapefruit, blood oranges and other foods.\n");
      printf("(3)Fatty fish such as salmon,  sardines,mackerel, herring and albacore tuna Walnuts and flaxseed Polyphenols in Tea green or blacktea.\n");
      printf(" (4)two Brazil nuts a day Meats such as chicken and grass-fed beef\n");
      printf("(5)oranges, lemons, limes, strawberries, raspberries and certain vegetables, including leafy greens, broccoli and bell peppers.\n");
      break;
    }
    case 2:
    {
      printf(" (1)Apples and Oranges,salmon,beans,Ginger,turmericSpinach, Pomegranates,Tomato juice, Beets and beet, greens, Peppers,apples,Pumpkin,Turmeric,Tomato and tomato products, Blueberries,Green tea,Red cabbage,Olive oil,Yogurt,Brazil nuts\n");
      printf("(2)\tcoffee ,cocoa\n");
      break;
    }
    case 3:
    {
      printf("(1)Vitamin D-rich foods, such as milk and eggs Beta carotene-rich vegetables, such as carrots and leafy greens Magnesium-rich foods, such as spinach and pumpkin seeds\n(2)     carrotscantaloupe ,sweet potatoes ,leafy greens, such as romaine lettuce, kale, and spinach  ,broccoli \n");
      printf(" (3) spinach,pumpkin seeds,Swiss chard,dark chocolate,salmon\n");
      break;
    }
    case 4:
    {
      printf(" (1)Complex carbohydrates, fresh fruit and starchy vegetables,whole grains,whole grain bread and pasta,beans and lentils,Fiber-rich foods,beans and lentils,fruits and vegetables,nuts and seeds,whole grains, such as oats,vegetables\n");
      printf(" (2)Protein,meat and poultry,fish,eggs,nuts and seeds,legumes,tofu,cheese,milk,Mono and polyunsaturated fats, certain vegetable oils, such as olive oil and avocado oil,certain fish, including salmon,nuts and seeds,avocados\n");
      break;
    }
    case 5:
    {
      printf("(1) Dark Leafy Greens,Walnuts, Avocado, Berries,mushrooms,onions,tomotoes,beans, seeds,apples, Tea,Coffee,Grapefruit,Blueberries.\n");
      printf("(2) Cranberries,Grapes,Pear Beetroot juice, Brussels sprouts, broccoli, and mustard greens.\n");
      break;
    }
    case 6:
    {
      printf("(1)Coffee, Beans, Greens,And soy, fish, Oatmeal for fiber,Nuts,Turmeric,Sunflower seeds,Garlic.\n");
      break;
      }
      case 7:
      {
          printf("(1)Broth , Chicken soup , Ice pops, Citrus fruit, such as orangesand grapefruits,Broccoli,Brusselssprouts,Cantaloupe,Kiwi,Peppers,Potatoes,Strawberries tomatoes, Herbal tea,Garlic\n");
      break;
    }
   case 8:
    {
      printf("(1) Oranges,Whole grains,Green vegetables, Yoghurt ,Protein rich food,Honey,Turmeric,ginger milk \n");
      break;
      }
    case 9:
    {
      printf("(1)whole grainslegumesunprocessed fruits and vegetables,yellow and orange fruits and vegetables such as carrots, apricots, and sweet potatoes,spinach and other dark green and leafy vegetables,tomatoes,blueberries,whole-wheat bread,brown rice,quinoa,turkey,pumpkin seeds,beans, peas, and lentilssalmon, mackerel, and other kinds of fatty fishnuts.\n");
      break;
    }
    case 10:
    {
      printf(" (1)eggs,Berries, Spinach,Fatty fish,Sweet pototoes, Avocados,Nuts, Seeds, Sweet peppers.\n");
      printf("(2) Oyesters, Beans,Soybeans, Meat.\n");
      break;
    }
   case 11:
    {
      printf("(1) Apples,Alfalfa sprouts, Beets,Avocados,Cranberries, Flaxseed,Oranges,Papayas,Pumpkins,Quinoa,Raspberries,Spinach,Sweetpotatoes,Turkey,Walnuts,Watercress,Yoghurt.\n");
      printf("(1) Vitamin D-rich foods, such as milk and eggs,Beta carotene-rich vegetables, such as carrots and leafy greens ,Magnesium-rich foods, such as spinach and pumpkin seeds, carrots,cantaloupe,sweet potatoes,leafy greens, such as romaine lettuce, kale, and spinach,broccoli,Swiss chard,dark chocolate,salmon,bananas.\n");
      break;
    }
   case 12:
    {
      printf("(1)Banana,Oranges,Apricots,Melon, like cantaloupe, honeydew and watermelon,\n(2)Dark leafy greens, like spinach and kale,Potatoes,Sweet Potatoes,Winter Squash, like acorn or butternut,Beets,Beans and legumes,\nYogurt,Kefir,Salmon,Almonds, walnuts and other nuts and seeds.\n");
      break;
    }
   case 13:
    {
      printf("(1)fruits and vegetables,nuts and seeds,beans and legumes,fish and seafood,whole grains,plant-based oils, such as olive oil,eggs (you can eat up to six per week),leanmeats,skinless poultry.\n");
      break;
    }
    case 14:
    {
      printf("(1)Fruits and Vegetables\n(2)Protein\n(3)meats, poultry, fish, beans, peas, eggs, nuts and seeds\n(4)quinoa, brown rice and non-instant oatmeal.\n(5)Eat Soups and Liquids During the Initial Detox.\n");
      break;
    }
    case 15:
    {
        printf("(1)Fatty fish\n (2)Eggs\n (3)Pumpkin seeds\n (4)Dark chocolate\n (5) turmeric \n(6) chamomile\n (7)yoghurt\n(8) green tea \n(9)brazil nuts\n (10)tryptophan-containing foods, such as eggs, dark chocolate, cheese, pineapple, bananas, oats, and tofu\n (11)nuts, especially almonds\n (11)chia seeds \n (12)protein sources, such as lean meat, fish, nuts, and dairy\n spinachTrusted Source and Swiss chardTrusted Source\n (13)berries, cherries, and citrus \n ");
    }
    default :
    {
      printf("You Choose Wrong option.");
    }
  
    return 0;
   }
}
