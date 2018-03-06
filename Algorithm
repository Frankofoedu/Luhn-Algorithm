  static bool validate(string number)
        {
            number = number.Replace(" ", "");

            var numList = number.ToList();

            if (numList.Count % 2 == 0)
            {
                int sum = 0;
                for (int i = 0; i < numList.Count; i = i + 2)
                {
                    var digit = Convert.ToInt32(numList[i].ToString()) * 2;
                    int newdigit;
                    if (digit - 10 >= 0)
                    {
                        newdigit = (digit / 10) + (digit % 10);
                        numList[i] = Convert.ToChar(newdigit.ToString());
                    }
                    else
                    {

                        numList[i] = Convert.ToChar(digit.ToString());
                    }
                    
                }


                foreach (var item in numList)
                {
                    sum =+ Convert.ToInt32(item.ToString());
                }


                //4th step
                if (sum % 10 == 0)
                {
                    return true;
                }
                else
                {
                    return false;
                }
            }
            else
            {
                int sum = 0;
                for (int i = 1; i < numList.Count; i = i + 2)
                {
                    var t = Convert.ToInt32(numList[i].ToString());
                    var digit = Convert.ToInt32(numList[i].ToString()) * 2;
                    int newdigit;
                    if (digit - 10 >= 0)
                    {
                        newdigit = (digit / 10) + (digit % 10);
                        numList[i] = Convert.ToChar(newdigit.ToString());
                    }
                    else
                    {

                        numList[i] = Convert.ToChar(digit.ToString());
                    }

                }


                foreach (var item in numList)
                {
                    sum = +Convert.ToInt32(item.ToString());
                }


                //4th step
                if (sum % 10 == 0)
                {
                    return true;
                }
                else
                {
                    return false;
                }
                

            }
        }
