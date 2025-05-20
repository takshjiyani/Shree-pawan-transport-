import { Card, CardContent } from "@/components/ui/card";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { Textarea } from "@/components/ui/textarea";
import { MapPin, Truck } from "lucide-react";

export default function ShreePawanTransport() {
  return (
    <div className="min-h-screen bg-gradient-to-r from-blue-500 to-green-400 text-white font-sans">
      <header className="p-6 text-center text-4xl font-bold shadow-lg bg-opacity-70 bg-blue-600">
        Shree Pawan Transport
      </header>

      <section className="p-6 text-center">
        <h2 className="text-3xl font-semibold mb-4">About Us</h2>
        <p className="max-w-2xl mx-auto">
          Shree Pawan Transport has been a trusted name in transportation for over 4 years. We specialize in dependable logistics and transport services across the region.
        </p>
      </section>

      <section className="p-6 bg-white text-black">
        <h2 className="text-3xl font-semibold text-center mb-6">Our Services</h2>
        <Card className="max-w-2xl mx-auto">
          <CardContent className="p-4">
            <h3 className="text-xl font-bold mb-2">Full Truck Load</h3>
            <p>Reliable and timely full truck load transportation solutions for all cargo types.</p>
          </CardContent>
        </Card>
      </section>

      <section className="p-6 text-center">
        <h2 className="text-3xl font-semibold mb-6">Our Fleet</h2>
        <div className="flex justify-center items-center gap-4">
          <Truck className="w-16 h-16" />
          <p className="text-lg">We provide all types of trucks for your transport needs.</p>
        </div>
      </section>

      <section className="p-6 bg-white text-black">
        <h2 className="text-3xl font-semibold text-center mb-6">Book a Truck</h2>
        <form className="max-w-xl mx-auto space-y-4">
          <Input placeholder="Your Name" required />
          <Input placeholder="Phone Number" required />
          <Input placeholder="Pickup Location" required />
          <Input placeholder="Drop Location" required />
          <Textarea placeholder="Additional Details" />
          <Button className="w-full bg-blue-600 hover:bg-blue-700">Submit Booking</Button>
        </form>
      </section>

      <section className="p-6 text-center">
        <h2 className="text-3xl font-semibold mb-4">Contact Us</h2>
        <p><strong>Phone:</strong> 9512572475</p>
        <p><strong>Email:</strong> shreepawant@gmail.com</p>
        <p><strong>Address:</strong> FF-6, Takshila Gallariya Mall, Vastral, Ahmedabad</p>
        <div className="flex justify-center mt-4">
          <MapPin className="w-6 h-6 mr-2" />
          <a 
            href="https://maps.google.com/?q=Takshila+Gallariya+Mall+Vastral+Ahmedabad"
            className="underline text-white"
            target="_blank"
          >
            View on Map
          </a>
        </div>
      </section>

      <section className="p-6 bg-blue-900 bg-opacity-80">
        <h2 className="text-3xl text-center font-semibold mb-4">Live Tracking</h2>
        <p className="text-center max-w-2xl mx-auto">
          Real-time truck tracking coming soon! For now, please call us for updates.
        </p>
      </section>

      <footer className="text-center p-4 text-sm bg-blue-800">
        © 2025 Shree Pawan Transport. All rights reserved.
      </footer>
    </div>
  );
} na
