package com.kuliah;

import java.util.ArrayList;

public class TugasList {

    public static void main(String[] args) {

// PROGRAM LIST

        ArrayList<String> mhs = new ArrayList<>();

//      menambahkan daftar nama
        mhs.add("Devi");
        mhs.add("Dina");
        mhs.add("Dania");

//      menambahkan daftar NIM
        mhs.add("210555");
        mhs.add("210666");
        mhs.add("210777");

        System.out.println("Daftar Nama dan NIM Mahasiswa sebelum diurutkan");
        for (int i = 0; i < mhs.size(); i++) {
            System.out.println("\t index-"+ i +" = " + mhs.get(i));
        }

        System.out.println("\n Daftra Nama dan NIM Mahasiswa setelah diurutkan");
        System.out.println("======================================================\n");
        for (int i = 0; i < 3; i++){
            System.out.println("Nama \t: " + mhs.get(i));
            System.out.println("NIM \t: " + mhs.get(i+3));
            System.out.println("======================================");
        }
    }
}
