#include <stolio.h>
# define size s
int queue Lsizes
int front =-1, rear =-lj
void enqueuel)
ink value;
if (rear==size-l)
printf ("Enler value :"();
Scanf (110%oc", & value ) ;
if (front = = - 1)
f ront = 0ز
rear tt;
queue [rear) = value;
printf ("Value inserted In");
33
void dequeuel)
if (front ==-1 /font> rear) printf ("'Queue is emplyin");
3
elsef
printf ("Deleted value = odIn", quenciEronb]);
front t+;
33
void display ()
int i;
if (font== -1 ll front>rear)
{
else
printf (Queue elements are: ");
for Ci = Front; i (=rear ;i ++) .
Printf (*lod", queue [i]);
printf ("%od", queue [i]) ;
prinkfC"In");
int main ()
そ
int choice;
while (1)
printf ("\n l. Enqueue "); printf ("In 2. Dequeue "); printf (" In 3. Display"); printf (" In 4. Exit" );
printf ("In Enter your choice:");
Scan F("o%ocl", &choice);
switch (choice)
Lase l'.
enqueue ();
break;
case 2:
dequenc();
break;
Case 3:
display c); break;
Case 4: returno;
