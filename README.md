class HelloWorld { static void bubbleSort(int[] arr) {
int n = arr.length;
int temp = 0;
for(int i=0; i < n; i++){
for(int j=1; j < (n-i); j++){
if(arr[j-1] > arr[j]){
temp = arr[j-1];
arr[j-1] = arr[j];
arr[j] = temp;
}
}
}
public static void main( String []args ) { String tested = "This is going to be the ultimate test of your application and its working"; System.out.println( "Hello World this is America, the greatest nation!" ); Double val = 4.00D; String notHardCoded = String.valueOf(val); Object obj = new Object(); }

public void addNode(int data) {    
    Node newNode = new Node(data);    
    if(head == null) {    
        head = newNode;    
        tail = newNode;    
    }    
    else {    
        tail.next = newNode;    
        tail = newNode;    
    }    
}    

String conclusion = "This is a random code, it doesn't even make sense, what is even happening in this world";
}
