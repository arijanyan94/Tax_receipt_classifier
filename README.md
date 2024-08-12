#  Tax receipt Classifier #

## Objectives ##

This Jupiter notebook classifies the dataset to given categories, which are
**['beer','cheese','rice','meat','dairy','dessert','tomatoes']** and additionaly **'else'** class.
I added the 'else' class for not confusing the accuracy, because there are many items,
which are absolutely not related to the given 7 classes.

On this stage I have used only the **GOOD_NAME** columnfor classification. 
I have labeled all that column manualy, only for accuracy measurement, and it is used at the end of the notebook.

The overall accuracy is **75%** now, which can be improved.

The results are in **predicted_labels.csv** file.

## Potencial issues ##

1. Cottage cheese (tvorog) is always classified as cheese, but it has to be a dairy product
2. Kilki, sardina, etc are missclassified, but I don't even know what class are they, meat or else
3. Cherry tomatoes are classified as dessert, because most contries use them as fruits :D
4. 'Tan' is always classified as else, but it is a dairy product
5. Often jelly is classified as dairy, but is a dessert. Don't know the reason
