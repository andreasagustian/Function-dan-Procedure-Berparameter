/*
 * To change this license header, choose License Headers in Project Properties.
 * To change this template file, choose Tools | Templates
 * and open the template in the editor.
 */
package id.co.blits.tugasparameter.paket1;

/**
 *
 * @author ANDREAS AGUSTIAN ARDI
 */
//public class KelasUtama {

    /**
     * @param args the command line arguments
     */
    //public static void main(String[] args) {
     
class  kotak{
     int panjang;
     int lebar;
     int tinggi;
     int volume;
     
       public int HitungVolume(){
          volume = panjang * lebar * tinggi; 
          return volume;
     }
     public void SetData(int p, int l, int t){
          panjang = p;
          lebar = l;
          tinggi = t;
     }
 
     public static void main(String[] args){
          kotak obj = new kotak();
          obj.SetData(10,20,5);
          System.out.println("Volume Balok adalah " + obj.HitungVolume());
     }
}
   
    


