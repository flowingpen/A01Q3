A01Q3
=====
void middle (struct node *head)
{
struct node *temp=head, *ptemp=head;
while(ptemp)
{
ptemp=ptemp->next->next;
temp=temp->next;
}
printf("%d",temp=temp->data);
}
