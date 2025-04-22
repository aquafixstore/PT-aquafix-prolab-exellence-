# PT-aquafix-prolab-exellence-
Quality product fish care
import React from "react"; import { Button } from "@/components/ui/button"; import { Card, CardContent } from "@/components/ui/card";

export default function HomePage() { return ( <div className="p-4 space-y-6"> <h1 className="text-3xl font-bold text-center">PT Aquafix Prolab Exellence</h1> <p className="text-center text-gray-600">Spesialis Probiotik & Penjernih Air untuk Kolam dan Akuarium</p>

<div className="grid grid-cols-1 md:grid-cols-3 gap-4">
    <Card>
      <CardContent className="p-4 space-y-2">
        <img src="/images/ammonia_remover.jpg" alt="Ammonia Remover" className="w-full rounded" />
        <h2 className="text-xl font-semibold">Ammonia Remover</h2>
        <ul className="list-disc pl-5 text-sm">
          <li>Menjernihkan Air</li>
          <li>Menetralkan Amoniak</li>
          <li>Menstabilkan pH</li>
          <li>Berisi mikro bakteri pengurai</li>
        </ul>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-4 space-y-2">
        <img src="/images/water_cleaner.jpg" alt="Water Cleaner" className="w-full rounded" />
        <h2 className="text-xl font-semibold">Water Cleaner</h2>
        <ul className="list-disc pl-5 text-sm">
          <li>Mengikat logam berat</li>
          <li>Meningkatkan kualitas air</li>
          <li>Menjernihkan dan oksigenasi</li>
        </ul>
      </CardContent>
    </Card>

    <Card>
      <CardContent className="p-4 space-y-2">
        <img src="/images/paket_maximal.jpg" alt="Paket Penjernih Maximal" className="w-full rounded" />
        <h2 className="text-xl font-semibold">Paket Penjernih Maximal</h2>
        <ul className="list-disc pl-5 text-sm">
          <li>Anti Alga</li>
          <li>Penjernih logam berat & biologis</li>
          <li>Bakteri starter</li>
        </ul>
      </CardContent>
    </Card>
  </div>

  <div className="text-center space-y-3">
    <h2 className="text-2xl font-bold">Pesan Sekarang!</h2>
    <p>WhatsApp: <a href="https://wa.me/6285811551104" className="text-blue-600">0858-1155-1104</a></p>
    <p>Shopee: <a href="https://shopee.co.id/aquafixstore" className="text-orange-600">aquafixstore</a></p>
    <Button className="bg-green-600 hover:bg-green-700 text-white">Hubungi via WhatsApp</Button>
  </div>
</div>

); }


