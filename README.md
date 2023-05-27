# ExtendedArray
Method takes two parameters: a reference to an array that holds int values and an int variable. The method returns a copy of the array with the integer parameter added to the end of the array.


    public static void createExtendedArray(int[] array, int num)
      {
        int[] extendedArray = new int[array.length + 1];
        int i;
        for(i = 0; i < array.length; i++)
        {
          extendedArray[i] = array[i];

        }
        extendedArray[i] = num;

      }
