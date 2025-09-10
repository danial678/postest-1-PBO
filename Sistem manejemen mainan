/*
 * Click nbfs://nbhost/SystemFileSystem/Templates/Licenses/license-default.txt to change this license
 */

package main;
import java.util.ArrayList;
import java.util.Scanner;

/**
 *
 * @author Acer-GK
 */

public class main {
    
    // Inner class untuk menyimpan data mainan
    static class Mainan {
        String nama;
        String bahan;
        String tanggalProduksi;
        String kondisi;
        double harga;

        Mainan(String nama, String bahan, String tanggalProduksi, String kondisi, double harga) {
            this.nama = nama;
            this.bahan = bahan;
            this.tanggalProduksi = tanggalProduksi;
            this.kondisi = kondisi;
            this.harga = harga;
        }
    }

    public static void main(String[] args) {
        ArrayList<Mainan> koleksiMainan = new ArrayList<>();
        Scanner input = new Scanner(System.in);
        int pilihan;

        do {
            System.out.println("======================================");
            System.out.println("        MANAJEMEN KOLEKSI MAINAN");
            System.out.println("======================================");
            System.out.println("1. Tambah Mainan");
            System.out.println("2. Lihat Koleksi Mainan");
            System.out.println("3. Ubah Mainan");
            System.out.println("4. Hapus Mainan");
            System.out.println("5. Keluar");
            System.out.println("======================================");
            System.out.print("Pilih menu (1-5): ");
            pilihan = input.nextInt();
            input.nextLine(); // buang enter

            switch (pilihan) {
                case 1:
                    System.out.println("---- TAMBAH MAINAN ----");
                    System.out.print("Masukkan nama mainan        : ");
                    String nama = input.nextLine();
                    System.out.print("Masukkan bahan mainan       : ");
                    String bahan = input.nextLine();
                    System.out.print("Masukkan tanggal produksi(20-05-2000) : ");
                    String tanggal = input.nextLine();
                    System.out.print("Masukkan kondisi (Baru/Bekas): ");
                    String kondisi = input.nextLine();
                    System.out.print("Masukkan harga mainan (Rp)  : ");
                    double harga = input.nextDouble();
                    input.nextLine();

                    koleksiMainan.add(new Mainan(nama, bahan, tanggal, kondisi, harga));
                    System.out.println("Mainan berhasil ditambahkan!");
                    break;

                case 2:
                    System.out.println("____ DAFTAR KOLEKSI MAINAN ____");
                    if (koleksiMainan.isEmpty()) {
                        System.out.println("Belum ada mainan dalam koleksi.");
                    } else {
                        for (int i = 0; i < koleksiMainan.size(); i++) {
                            Mainan mainan = koleksiMainan.get(i);
                            System.out.println((i + 1) + ". Nama: " + mainan.nama + 
                                               " | Bahan: " + mainan.bahan + 
                                               " | Tgl Produksi: " + mainan.tanggalProduksi +
                                               " | Kondisi: " + mainan.kondisi +
                                               " | Harga: Rp" + mainan.harga);
                        }
                    }
                    break;

                case 3:
                    System.out.println("____ DAFTAR KOLEKSI MAINAN ____");
                    if (koleksiMainan.isEmpty()) {
                        System.out.println("Belum ada mainan dalam koleksi.");
                    } else {
                        for (int i = 0; i < koleksiMainan.size(); i++) {
                            Mainan mainan = koleksiMainan.get(i);
                            System.out.println((i + 1) + ". Nama: " + mainan.nama + 
                                               " | Bahan: " + mainan.bahan + 
                                               " | Tgl Produksi: " + mainan.tanggalProduksi +
                                               " | Kondisi: " + mainan.kondisi +
                                               " | Harga: Rp" + mainan.harga);
                        }
                    }
                    System.out.println("==== UBAH DATA MAINAN ====");
                    if (koleksiMainan.isEmpty()) {
                        System.out.println("Belum ada data untuk diubah.");
                    } else {
                        System.out.print("Masukkan nomor mainan yang ingin diubah: ");
                        int nomorUbah = input.nextInt();
                        input.nextLine();

                        if (nomorUbah > 0 && nomorUbah <= koleksiMainan.size()) {
                            Mainan mainan = koleksiMainan.get(nomorUbah - 1);
                            System.out.println("Data lama -> Nama: " + mainan.nama + ", Bahan: " + mainan.bahan + 
                                               ", Tgl Produksi: " + mainan.tanggalProduksi +
                                               ", Kondisi: " + mainan.kondisi +
                                               ", Harga: Rp" + mainan.harga);
                            
                            System.out.print("Masukkan nama mainan baru        : ");
                            mainan.nama = input.nextLine();
                            System.out.print("Masukkan bahan mainan baru       : ");
                            mainan.bahan = input.nextLine();
                            System.out.print("Masukkan tanggal produksi baru   : ");
                            mainan.tanggalProduksi = input.nextLine();
                            System.out.print("Masukkan kondisi baru (Baru/Bekas): ");
                            mainan.kondisi = input.nextLine();
                            System.out.print("Masukkan harga baru (Rp)         : ");
                            mainan.harga = input.nextDouble();
                            input.nextLine();

                            System.out.println("Data mainan berhasil diubah!");
                        } else {
                            System.out.println("Nomor tidak valid.");
                        }
                    }
                    break;

                case 4:
                    System.out.println("____ DAFTAR KOLEKSI MAINAN ____");
                    if (koleksiMainan.isEmpty()) {
                        System.out.println("Belum ada mainan dalam koleksi.");
                    } else {
                        for (int i = 0; i < koleksiMainan.size(); i++) {
                            Mainan mainan = koleksiMainan.get(i);
                            System.out.println((i + 1) + ". Nama: " + mainan.nama + 
                                               " | Bahan: " + mainan.bahan + 
                                               " | Tgl Produksi: " + mainan.tanggalProduksi +
                                               " | Kondisi: " + mainan.kondisi +
                                               " | Harga: Rp" + mainan.harga);
                        }
                    }
                    System.out.println("---- HAPUS MAINAN ----");
                    if (koleksiMainan.isEmpty()) {
                        System.out.println("Belum ada data untuk dihapus.");
                    } else {
                        System.out.print("Masukkan nomor mainan yang ingin dihapus: ");
                        int nomorHapus = input.nextInt();
                        input.nextLine();

                        if (nomorHapus > 0 && nomorHapus <= koleksiMainan.size()) {
                            koleksiMainan.remove(nomorHapus - 1);
                            System.out.println("Mainan berhasil dihapus!");
                        } else {
                            System.out.println("Nomor tidak valid.");
                        }
                    }
                    break;

                case 5:
                    System.out.println("Terima kasih telah menggunakan program ini!");
                    break;

                default:
                    System.out.println("Pilihan tidak tersedia. Silakan coba lagi.");
            }
            System.out.println();
        } while (pilihan != 5);

        input.close();
    }
}
