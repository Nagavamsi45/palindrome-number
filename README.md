# palindrome-number
A palindrome is a word, phrase, number, or sequence of symbols that reads the same backwards as forwards. The word "palindrome" comes from the Greek word palíndromos, which means "running back again".

class Main{  
 public static void main(String args[]){  
  int r,sum=0,temp;    
  int n=329;//It is the number variable to be checked for palindrome  
  
  temp=n;    
  while(n>0){    
   r=n%10;  //getting remainder  
   sum=(sum*10)+r;    
   n=n/10;    
  }    
  if(temp==sum)    
   System.out.println("palindrome number ");    
  else    
   System.out.println("not palindrome");
}
}
