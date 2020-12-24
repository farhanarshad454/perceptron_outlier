# perceptron_outlier

Perceptron is use for the purpose of removing outlier(parameter values which is out of range)
formulas which are used to find perceptron and perceptron value are:

                PERCENTILE (Not percentage)(place of the value in sequence)

percentile = ((number of values below x) + 0.5)/total number of values 
percentile = ((number of values below x) + 1)/total number of values

                  VALUE OF PERCENTILE 
                  
C=(N.P)/100
C = value of percentile , N = Total no of values in colum , P = percentile 
for example :-
np.array[1,2,6,9,10,11,15,20]
c= (8 * 95)/100

C= 7.5 (means '8')
8th value is 20 

Note :- 
if c = float value than assend it e.g 7.5 convert to  8
if c= whole number than the mean by ( sum of whole number , further number and than devide by 2)
e.g 

c= 6 than 
        mean =(( 6th + 7th )values)/2
        
