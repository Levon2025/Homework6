# Homework6
#include <stdio.h>
char to_upper(char c){
  if(c>='a'&& c<= 'z'){
    return c & ~32; 
  }
  return c;
}
int main(){
  char input = 'b';
  char output = to_upper(input);
  printf("input:%c, output:%c\n",input, output);
  return 0;
}
