# GENRICS
pACKAGE PACK1;
public class Cnt {

    Public static <T> int cnt(T[] arr, T tgt) {
        int n = 0;
        for (T e : arr) {
            if (e.equals(tgt)) {
                n++;
            }
        }
        return n;
    }

    public static void main(String[] args) {
        Integer[] a = {1, 2, 3, 2, 4, 2, 5};
        System.out.println("2 -> " + cnt(a, 2));
    }
