# 223project
import java.util.*;
import java.io.*;

public class Card
{
private String Suit;
private int value;

public Card(String s, int v)
{
Suit=s;
value=v;

}

public void setSuit(String s)
{

Suit=s;

}

public void setValue(int v)
{

value=v;

}

public int getValue()
{
return value;
}

public String getSuit()
{

return Suit;

}

}
