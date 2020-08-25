# Machine-Learning-Challenge-Adopt-a-Buddy
## The above code achieved accuracy of 89.25% 
Problem statement

Having a pet is one of life’s most fulfilling experiences. Your pets spoil you with their love, compassion and loyalty. And dare anyone lay a finger on you in your pet’s presence, they are in for a lot of trouble. Thanks to social media, videos of clumsy and fussy (yet adorable) pets from across the globe entertain you all day long. Their love is pure and infinite. So, in return, all pets deserve a warm and loving family, indeed. And occasional boops, of course.

Numerous organizations across the world provide shelter to all homeless animals until they are adopted into a new home. However, finding a loving family for them can be a daunting task at times.  This International Homeless Animals Day, we present a Machine Learning challenge to you: Adopt a buddy.

The brighter side of the pandemic is an increase in animal adoption and fostering. To ensure that their customers stay indoors, a leading pet adoption agency plans on creating a virtual-tour experience, showcasing all animals available in their shelter. To enable that, you have been tasked to build a Machine Learning model that determines type and breed of the animal based on its physical attributes and other factors.

## Data
The data consists the following columns

Sl No.  Column Name	      Description
1   	  pet_id	          Unique Pet Id
2	      issue_date	      Date on which the pet was issued to the shelter
3	      listing_date	    Date when the pet arrived at the shelter
4	      condition        	Condition of the pet
5	      color_type	      Color of the pet
6	      length(m)	        Length of the pet (in meter)
7	      height(cm)	      Height of the pet (in centimeter)
8	      X1,X2	            Anonymous columns
9	      breed_category	  Breed category of the pet (target variable)
10	    pet_category	    Category of the pet (target variable)

### sample_submission:

pet_id      breed_category   pet_category
ANSL_69903  0                1
ANSL_66892  0                2
ANSL_69750  2                4
ANSL_71623  0                2
ANSL_57969  0                1
