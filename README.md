# 25331A05H1-Built-in-functions-
#include <stdio.h> 
#include <string.h> 
int main() { 
    char str1[100], str2[100]; 
    char copyStr[100]; 
    printf("Enter first string: "); 
    scanf("%s", str1); 
    printf("Enter second string: "); 
    scanf("%s", str2); 
    /* 1. Length */ 
    printf("\nLength of first string: %lu", strlen(str1)); 
    printf("\nLength of second string: %lu", strlen(str2)); 
    /* 2. Copy */ 
    strcpy(copyStr, str1); 
    printf("\nCopied string: %s", copyStr); 
    /* 3. Concatenation */ 
    strcat(str1, str2); 
    printf("\nConcatenated string: %s", str1); 
    /* 4. Comparison */ 
    if(strcmp(copyStr, str2) == 0) 
        printf("\nStrings are equal"); 
    else 
        printf("\nStrings are not equal"); 
    return 0; 
}
