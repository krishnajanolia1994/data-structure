#include<iostream.h>
#include<conio.h>
struct tree
{
  int info;
  struct tree *left,*right;
}


//add a node in tree
void add(struct tree * TREE,int flag)
{
    struct tree *newtree=(struct tree *)malloc(sizeof(struct tree));
    newtree->right=NULL;
    newtree->left=NULL;
    if(TREE!=NULL)
    {
      if(flag)
        TREE->right=newtree;
      else
        TREE->left=newtree;
    }
}



void main()
{
  struct tree *newtree=NULL;
  add(newtree,1);
  add(newtree,1);
  add(newtree,0);
  add(newtree->left,1);
  add(newtree->left,0);
  getch();
}
