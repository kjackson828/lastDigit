# lastDigit
public boolean lastDigit(int a, int b) {
  if((a == 10 && b == 0) || (b == 10 && a == 0)){
    return true;
  }
  else if((b > 10) && (b % 10 == a)){
    return true;
  }
  else if((a > 10) && (a % 10 == b)){
    return true;
  }
  return false;
}
