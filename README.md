# PTC
How to use:
1) Clone this project and extort all file inside your maven repo:
com/ptc/devoir/solution/1.0

2) Create a new wave project and add this dependency inside pom.xml file:

<dependencies>
        <dependency>
            <groupId>com.ptc.devoir</groupId>
            <artifactId>solution</artifactId>
            <version>1.0</version>
        </dependency>
</dependencies>

3) after that you can use solution method anywhere:

Exemple :
public static void main(String[] args) {
        System.out.println(Solution.partition(new int[] {1,2,3,4,5}, 3));
}

4) Enjoy !