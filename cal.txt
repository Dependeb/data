 echo "Enter 2 numbers:"
read a
read b
echo "menu"
echo "1.Addition"
echo "2.Subtraction"
echo "3.Multiplication"
echo "4.Division"
read ch
case $ch in
1)res=`echo $a+$b|bc`
 ;;
2)res=`echo $a-$b|bc`
 ;;
3)res=`echo $a*$b|bc`
 ;;
4)res=`echo $a/$b|bc`
 ;;
5)echo "Invalid Choice !!!!!!"
 ;;
esac
echo "Result=$res"
