
# coding: utf-8

# In[3]:


import math
def is_year_leap(year):
    first_condition =  year/4 - math.floor(year/4) 
    second_condition = year/100 - math.floor(year/100) 
    third_condition = year/400 - math.floor(year/400) 
    
    if(first_condition == 0):
        if(first_condition == 0 and second_condition !=0):
            #print("Високосный")
            value = True
        elif(second_condition == 0 and third_condition == 0):
            #print("Високосный")
            value = True
        elif(second_condition == 0 and third_condition != 0):
            #print("Не високосный")
            value = False
    else:
        #print("Не високосный")
        value = False
    return value

