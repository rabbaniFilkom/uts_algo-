# uts_algo-
membuat identitas menggunakan bahasa java
package uprak_algoritma;

public class Uprak_algoritma {

    public static void main(String[] args) {
        // membuat variabel
        String NAMA, NIM, FAKULTAS, PRODI;
        int SKS, SEMESTER;
        float IPK;
        
        //mengisi variabel
       
        NAMA = "Muhammad Rabbani Razaq";
        NIM = "I.2310856";
        FAKULTAS = "ILMU KOMPUER";       
        PRODI = "ILMU KOMPUTER";
        SEMESTER = 1;
        SKS  = 20;      
        IPK = (float) 3.8;
        
        //mencetak ke layar isi variabel
        System.out.println("=====================================");
        System.out.println("         IDENTITAS MAHASISWA            ");          
        System.out.println("=====================================");
        System.out.println(" Nama      : " + NAMA);
        System.out.println(" Nim       : " + NIM);
        System.out.println(" Fakultas  : " + FAKULTAS);
        System.out.println(" Prodi     : " + PRODI);
        System.out.println(" Semester  : " + SEMESTER);
        System.out.println(" Sks       : " + SKS);
        System.out.println(" Ipk       : " + IPK);
        System.out.println("=====================================");
        System.out.println("        UNIVERSITAS DJUANDA");
        System.out.println("=====================================");
                
    }
    
}
