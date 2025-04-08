[(https://github.com/Constructschon/https-github.com-Diamond24-7-constructschon)](https://github.com/Diamond24-7/constructschon.git)
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section */}
      <section className="relative h-[600px] flex items-center justify-center bg-gradient-to-r from-purple-600 to-blue-600">
        <div className="container mx-auto px-4 text-center text-white">
          <h1 className="text-5xl font-bold mb-6">Welcome to Our Business</h1>
          <p className="text-xl mb-8">Delivering excellence in everything we do</p>
          <Button size="lg" variant="secondary">Get Started</Button>
        </div>
      </section>

      {/* Services Section */}
      <section className="py-20 bg-gray-50">
        <div className="container mx-auto px-4">
          <h2 className="text-3xl font-bold text-center mb-12">Our Services</h2>
          <div className="grid md:grid-cols-3 gap-8">
            <Card>
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4">Service 1</h3>
                <p className="text-gray-600">Comprehensive solutions tailored to your needs</p>
              </CardContent>
            </Card>
            <Card>
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4">Service 2</h3>
                <p className="text-gray-600">Expert consultation and strategic planning</p>
              </CardContent>
            </Card>
            <Card>
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4">Service 3</h3>
                <p className="text-gray-600">Innovative solutions for modern challenges</p>
              </CardContent>
            </Card>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section className="py-20">
        <div className="container mx-auto px-4">
          <div className="max-w-3xl mx-auto text-center">
            <h2 className="text-3xl font-bold mb-8">About Us</h2>
            <p className="text-gray-600 mb-8">
              We are a dedicated team of professionals committed to delivering exceptional 
              results for our clients. With years of experience and a passion for excellence, 
              we help businesses achieve their goals.
            </p>
            <Button variant="outline">Learn More</Button>
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section className="py-20 bg-gray-50">
        <div className="container mx-auto px-4 text-center">
          <h2 className="text-3xl font-bold mb-8">Get in Touch</h2>
          <p className="text-gray-600 mb-8">Ready to start your journey with us?</p>
          <Button>Contact Us</Button>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-12">
        <div className="container mx-auto px-4">
          <div className="text-center">
            <p className="mb-4">© 2024 Your Business Name. All rights reserved.</p>
            <div className="space-x-4">
              <a href="#" className="hover:text-gray-300">Privacy Policy</a>
              <a href="#" className="hover:text-gray-300">Terms of Service</a>
            </div>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default Index;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section */}
      <section className="relative h-screen flex items-center justify-center">
        <div className="absolute inset-0 z-0">
          <img 
            src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b" 
            alt="Construction Site" 
            className="w-full h-full object-cover brightness-50"
          />
        </div>
        <div className="container mx-auto px-4 text-center relative z-10">
          <h1 className="text-6xl font-bold mb-6 text-white">Building Excellence</h1>
          <p className="text-xl mb-8 text-gray-200 max-w-2xl mx-auto">
            Your trusted partner in construction, delivering quality projects with precision and expertise.
          </p>
          <Button size="lg" variant="secondary" className="hover:scale-105 transition-transform">
            View Our Projects
          </Button>
        </div>
      </section>

      {/* Services Section */}
      <section className="py-24 bg-gray-50">
        <div className="container mx-auto px-4">
          <h2 className="text-4xl font-bold text-center mb-16">Our Services</h2>
          <div className="grid md:grid-cols-3 gap-8">
            <Card className="hover:shadow-lg transition-shadow">
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4">Commercial Construction</h3>
                <p className="text-gray-600">Expert solutions for your commercial building needs, from concept to completion.</p>
              </CardContent>
            </Card>
            <Card className="hover:shadow-lg transition-shadow">
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4">Residential Projects</h3>
                <p className="text-gray-600">Creating beautiful, functional spaces for families and communities.</p>
              </CardContent>
            </Card>
            <Card className="hover:shadow-lg transition-shadow">
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4">Renovation Services</h3>
                <p className="text-gray-600">Transforming existing spaces with modern upgrades and improvements.</p>
              </CardContent>
            </Card>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section className="py-24">
        <div className="container mx-auto px-4">
          <div className="max-w-3xl mx-auto text-center">
            <h2 className="text-4xl font-bold mb-8">About Us</h2>
            <p className="text-gray-600 mb-8 text-lg">
              With years of experience in the construction industry, we pride ourselves on 
              delivering exceptional quality and service. Our team of professionals ensures 
              that every project is completed to the highest standards.
            </p>
            <Button variant="outline" className="hover:scale-105 transition-transform">
              Learn More About Us
            </Button>
          </div>
        </div>
      </section>

      {/* Projects Preview Section */}
      <section className="py-24 bg-gray-50">
        <div className="container mx-auto px-4">
          <h2 className="text-4xl font-bold text-center mb-16">Featured Projects</h2>
          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            {[1, 2, 3].map((item) => (
              <div key={item} className="group relative overflow-hidden rounded-lg">
                <img
                  src={`https://images.unsplash.com/photo-1531297484001-80022131f5a1?w=800`}
                  alt={`Project ${item}`}
                  className="w-full h-64 object-cover transition-transform duration-300 group-hover:scale-110"
                />
                <div className="absolute inset-0 bg-black bg-opacity-50 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                  <Button variant="secondary">View Project</Button>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section className="py-24">
        <div className="container mx-auto px-4 text-center">
          <h2 className="text-4xl font-bold mb-8">Get in Touch</h2>
          <p className="text-gray-600 mb-8 max-w-2xl mx-auto">
            Ready to start your next construction project? Contact us today for a consultation.
          </p>
          <Button size="lg" className="hover:scale-105 transition-transform">Contact Us</Button>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-gray-900 text-white py-16">
        <div className="container mx-auto px-4">
          <div className="grid md:grid-cols-3 gap-8">
            <div>
              <h3 className="text-xl font-bold mb-4">Contact Info</h3>
              <p className="mb-2">123 Construction Ave</p>
              <p className="mb-2">Vancouver, BC V6B 1A1</p>
              <p className="mb-2">Phone: (604) 555-0123</p>
              <p>Email: info@constructschon.ca</p>
            </div>
            <div>
              <h3 className="text-xl font-bold mb-4">Quick Links</h3>
              <ul className="space-y-2">
                <li><a href="#" className="hover:text-gray-300">Home</a></li>
                <li><a href="#" className="hover:text-gray-300">Services</a></li>
                <li><a href="#" className="hover:text-gray-300">Projects</a></li>
                <li><a href="#" className="hover:text-gray-300">About Us</a></li>
                <li><a href="#" className="hover:text-gray-300">Contact</a></li>
              </ul>
            </div>
            <div>
              <h3 className="text-xl font-bold mb-4">Business Hours</h3>
              <p className="mb-2">Monday - Friday: 8:00 AM - 5:00 PM</p>
              <p className="mb-2">Saturday: By Appointment</p>
              <p>Sunday: Closed</p>
            </div>
          </div>
          <div className="border-t border-gray-800 mt-12 pt-8 text-center">
            <p>© 2024 Constructschon. All rights reserved.</p>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default Index;
import type { Config } from "tailwindcss";

export default {
	darkMode: ["class"],
	content: [
		"./pages/**/*.{ts,tsx}",
		"./components/**/*.{ts,tsx}",
		"./app/**/*.{ts,tsx}",
		"./src/**/*.{ts,tsx}",
	],
	prefix: "",
	theme: {
		container: {
			center: true,
			padding: '2rem',
			screens: {
				'2xl': '1400px'
			}
		},
		extend: {
			colors: {
				// Brand Colors
				brand: {
					primary: '#C6007E',    // PANTONE 233 C
					secondary: '#009B77',   // PANTONE 3278 C
					gray: '#414042',        // Black 80%
					coral: '#FF808B',       // PANTONE 177 U
				},
				// ... keep existing code (existing color definitions)
			},
			// ... keep existing code (other theme configurations)
		}
	},
	plugins: [require("tailwindcss-animate")],
} satisfies Config;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section */}
      <section className="relative h-screen flex items-center justify-center">
        <div className="absolute inset-0 z-0">
          <img 
            src="https://images.unsplash.com/photo-1488590528505-98d2b5aba04b" 
            alt="Construction Site" 
            className="w-full h-full object-cover brightness-50"
          />
        </div>
        <div className="container mx-auto px-4 text-center relative z-10">
          <h1 className="text-6xl font-bold mb-6 text-white">Building Excellence</h1>
          <p className="text-xl mb-8 text-gray-200 max-w-2xl mx-auto">
            Your trusted partner in construction, delivering quality projects with precision and expertise.
          </p>
          <Button size="lg" className="bg-brand-primary hover:bg-brand-primary/90 text-white">
            View Our Projects
          </Button>
        </div>
      </section>

      {/* Services Section */}
      <section className="py-24 bg-gray-50">
        <div className="container mx-auto px-4">
          <h2 className="text-4xl font-bold text-center mb-16 text-brand-gray">Our Services</h2>
          <div className="grid md:grid-cols-3 gap-8">
            <Card className="hover:shadow-lg transition-shadow border-brand-secondary/20">
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4 text-brand-secondary">Commercial Construction</h3>
                <p className="text-brand-gray">Expert solutions for your commercial building needs, from concept to completion.</p>
              </CardContent>
            </Card>
            <Card className="hover:shadow-lg transition-shadow border-brand-secondary/20">
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4 text-brand-secondary">Residential Projects</h3>
                <p className="text-brand-gray">Creating beautiful, functional spaces for families and communities.</p>
              </CardContent>
            </Card>
            <Card className="hover:shadow-lg transition-shadow border-brand-secondary/20">
              <CardContent className="pt-6">
                <h3 className="text-xl font-semibold mb-4 text-brand-secondary">Renovation Services</h3>
                <p className="text-brand-gray">Transforming existing spaces with modern upgrades and improvements.</p>
              </CardContent>
            </Card>
          </div>
        </div>
      </section>

      {/* About Section */}
      <section className="py-24">
        <div className="container mx-auto px-4">
          <div className="max-w-3xl mx-auto text-center">
            <h2 className="text-4xl font-bold mb-8 text-brand-gray">About Us</h2>
            <p className="text-brand-gray mb-8 text-lg">
              With years of experience in the construction industry, we pride ourselves on 
              delivering exceptional quality and service. Our team of professionals ensures 
              that every project is completed to the highest standards.
            </p>
            <Button variant="outline" className="border-brand-secondary text-brand-secondary hover:bg-brand-secondary hover:text-white">
              Learn More About Us
            </Button>
          </div>
        </div>
      </section>

      {/* Projects Preview Section */}
      <section className="py-24 bg-gray-50">
        <div className="container mx-auto px-4">
          <h2 className="text-4xl font-bold text-center mb-16 text-brand-gray">Featured Projects</h2>
          <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
            {[1, 2, 3].map((item) => (
              <div key={item} className="group relative overflow-hidden rounded-lg">
                <img
                  src={`https://images.unsplash.com/photo-1531297484001-80022131f5a1?w=800`}
                  alt={`Project ${item}`}
                  className="w-full h-64 object-cover transition-transform duration-300 group-hover:scale-110"
                />
                <div className="absolute inset-0 bg-brand-primary/50 opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-center justify-center">
                  <Button variant="secondary" className="bg-white text-brand-primary hover:bg-white/90">View Project</Button>
                </div>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Contact Section */}
      <section className="py-24 bg-brand-secondary text-white">
        <div className="container mx-auto px-4 text-center">
          <h2 className="text-4xl font-bold mb-8">Get in Touch</h2>
          <p className="text-white/90 mb-8 max-w-2xl mx-auto">
            Ready to start your next construction project? Contact us today for a consultation.
          </p>
          <Button size="lg" className="bg-white text-brand-secondary hover:bg-white/90">Contact Us</Button>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-brand-gray text-white py-16">
        <div className="container mx-auto px-4">
          <div className="grid md:grid-cols-3 gap-8">
            <div>
              <h3 className="text-xl font-bold mb-4">Contact Info</h3>
              <p className="mb-2 text-white/80">123 Construction Ave</p>
              <p className="mb-2 text-white/80">Vancouver, BC V6B 1A1</p>
              <p className="mb-2 text-white/80">Phone: (604) 555-0123</p>
              <p className="text-white/80">Email: info@constructschon.ca</p>
            </div>
            <div>
              <h3 className="text-xl font-bold mb-4">Quick Links</h3>
              <ul className="space-y-2">
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Home</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Services</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Projects</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">About Us</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Contact</a></li>
              </ul>
            </div>
            <div>
              <h3 className="text-xl font-bold mb-4">Business Hours</h3>
              <p className="mb-2 text-white/80">Monday - Friday: 8:00 AM - 5:00 PM</p>
              <p className="mb-2 text-white/80">Saturday: By Appointment</p>
              <p className="text-white/80">Sunday: Closed</p>
            </div>
          </div>
          <div className="border-t border-white/20 mt-12 pt-8 text-center">
            <p className="text-white/60">© 2024 Constructschon. All rights reserved.</p>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default Index;
export default {
  darkMode: ["class"],
  content: [
    "./pages/**/*.{ts,tsx}",
    "./components/**/*.{ts,tsx}",
    "./app/**/*.{ts,tsx}",
    "./src/**/*.{ts,tsx}",
  ],
  prefix: "",
  theme: {
    container: {
      center: true,
      padding: '2rem',
      screens: {
        '2xl': '1400px'
      }
    },
    extend: {
      fontFamily: {
        azo: ['AZO Sans', 'sans-serif'],
        garamond: ['Garamond', 'serif'],
      },
      colors: {
        // ... keep existing code (brand colors)
      },
      borderRadius: {
        lg: 'var(--radius)',
        md: 'calc(var(--radius) - 2px)',
        sm: 'calc(var(--radius) - 4px)'
      },
      keyframes: {
        // ... keep existing code (keyframes)
      },
      animation: {
        // ... keep existing code (animations)
      }
    }
  },
  plugins: [require("tailwindcss-animate")],
} satisfies Config;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div className="w-full h-full bg-gradient-to-r from-brand-primary/90 to-brand-secondary/90" />
        </div>
        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
          >
            <h1 className="text-7xl font-black mb-6 text-white font-azo">
              Constructschön
            </h1>
            <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
              A boutique Canadian design-build firm delivering sustainable urban development
            </p>
            <Button 
              size="lg" 
              className="bg-white text-brand-primary hover:bg-white/90 font-azo"
            >
              Explore Our Projects
            </Button>
          </motion.div>
        </div>
      </section>

      {/* Services Section */}
      <section className="py-24 bg-white">
        <div className="container mx-auto px-4">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black text-center mb-16 text-brand-gray font-azo">
              Our Expertise
            </h2>
            <div className="grid md:grid-cols-3 gap-8">
              {[
                {
                  title: "Project Development",
                  description: "Comprehensive project management and development services for sustainable urban growth."
                },
                {
                  title: "Construction Management",
                  description: "Expert construction management with a focus on efficiency and sustainability."
                },
                {
                  title: "Sustainable Design",
                  description: "Innovative design solutions that prioritize environmental responsibility."
                }
              ].map((service, index) => (
                <motion.div
                  key={index}
                  initial={{ opacity: 0, y: 20 }}
                  whileInView={{ opacity: 1, y: 0 }}
                  transition={{ duration: 0.6, delay: index * 0.2 }}
                  viewport={{ once: true }}
                >
                  <Card className="hover:shadow-lg transition-all duration-300 border-none bg-gray-50">
                    <CardContent className="pt-6">
                      <h3 className="text-xl font-black mb-4 text-brand-primary font-azo">{service.title}</h3>
                      <p className="text-brand-gray font-garamond">{service.description}</p>
                    </CardContent>
                  </Card>
                </motion.div>
              ))}
            </div>
          </motion.div>
        </div>
      </section>

      {/* Featured Projects */}
      <section className="py-24 bg-gray-50">
        <div className="container mx-auto px-4">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black text-center mb-16 text-brand-gray font-azo">
              Featured Projects
            </h2>
            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
              {[
                "public/lovable-uploads/038e8f10-8c3c-4240-b9e5-41f0ebb477b3.png",
                "public/lovable-uploads/4def6ecd-67f4-4c43-b547-08ebac399e34.png",
                "public/lovable-uploads/c9e1a219-dd4c-4b54-bfe1-78a00641fe2c.png"
              ].map((image, index) => (
                <motion.div
                  key={index}
                  initial={{ opacity: 0, y: 20 }}
                  whileInView={{ opacity: 1, y: 0 }}
                  transition={{ duration: 0.6, delay: index * 0.2 }}
                  viewport={{ once: true }}
                  className="group relative overflow-hidden rounded-lg aspect-video"
                >
                  <img
                    src={image}
                    alt={`Project ${index + 1}`}
                    className="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110"
                  />
                  <div className="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex items-end p-6">
                    <Button variant="secondary" className="bg-white text-brand-primary hover:bg-white/90">
                      View Details
                    </Button>
                  </div>
                </motion.div>
              ))}
            </div>
          </motion.div>
        </div>
      </section>

      {/* Contact Section */}
      <section className="py-24 bg-brand-primary text-white">
        <div className="container mx-auto px-4 text-center">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black mb-8 font-azo">Let's Build Together</h2>
            <p className="text-white/90 mb-8 max-w-2xl mx-auto font-garamond text-lg">
              Ready to start your next construction project? Contact us today for a consultation.
            </p>
            <Button 
              size="lg" 
              className="bg-white text-brand-primary hover:bg-white/90 font-azo"
            >
              Get in Touch
            </Button>
          </motion.div>
        </div>
      </section>

      {/* Footer */}
      <footer className="bg-brand-gray text-white py-16">
        <div className="container mx-auto px-4">
          <div className="grid md:grid-cols-3 gap-8">
            <div>
              <h3 className="text-xl font-black mb-4 font-azo">Contact</h3>
              <p className="mb-2 text-white/80 font-garamond">647 678 5776</p>
              <p className="text-white/80 font-garamond">constructschon.ca</p>
            </div>
            <div>
              <h3 className="text-xl font-black mb-4 font-azo">Quick Links</h3>
              <ul className="space-y-2 font-garamond">
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Projects</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Services</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">About Us</a></li>
                <li><a href="#" className="text-white/80 hover:text-brand-coral transition-colors">Contact</a></li>
              </ul>
            </div>
            <div>
              <h3 className="text-xl font-black mb-4 font-azo">Location</h3>
              <p className="text-white/80 font-garamond">Edmonton, AB</p>
            </div>
          </div>
          <div className="border-t border-white/20 mt-12 pt-8 text-center">
            <p className="text-white/60 font-garamond">© 2024 Constructschön. All rights reserved.</p>
          </div>
        </div>
      </footer>
    </div>
  );
};

export default Index;

framer-motion@latest
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section */}
      // ... keep existing code (Hero section)

      {/* Services Section */}
      // ... keep existing code (Services section)

      {/* Featured Projects */}
      <section className="py-24 bg-gray-50">
        <div className="container mx-auto px-4">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black text-center mb-16 text-brand-gray font-azo">
              Featured Projects
            </h2>
            <div className="grid md:grid-cols-2 lg:grid-cols-3 gap-8">
              {[
                {
                  image: "public/lovable-uploads/038e8f10-8c3c-4240-b9e5-41f0ebb477b3.png",
                  title: "Urban Living Complex",
                  description: "A sustainable residential development featuring modern amenities and green spaces.",
                  location: "Downtown Edmonton",
                  year: "2023"
                },
                {
                  image: "public/lovable-uploads/4def6ecd-67f4-4c43-b547-08ebac399e34.png",
                  title: "Commercial Hub",
                  description: "Mixed-use commercial space designed for maximum efficiency and sustainability.",
                  location: "West Edmonton",
                  year: "2022"
                },
                {
                  image: "public/lovable-uploads/c9e1a219-dd4c-4b54-bfe1-78a00641fe2c.png",
                  title: "Eco-Friendly Office",
                  description: "Net-zero carbon emission office building with innovative design solutions.",
                  location: "South Edmonton",
                  year: "2023"
                }
              ].map((project, index) => (
                <motion.div
                  key={index}
                  initial={{ opacity: 0, y: 20 }}
                  whileInView={{ opacity: 1, y: 0 }}
                  transition={{ duration: 0.6, delay: index * 0.2 }}
                  viewport={{ once: true }}
                  className="group relative overflow-hidden rounded-lg"
                >
                  <div className="aspect-video relative overflow-hidden">
                    <img
                      src={project.image}
                      alt={project.title}
                      className="w-full h-full object-cover transition-transform duration-500 group-hover:scale-110"
                    />
                    <div className="absolute inset-0 bg-gradient-to-t from-black/70 to-transparent opacity-0 group-hover:opacity-100 transition-opacity duration-300 flex flex-col justify-end p-6">
                      <h3 className="text-xl font-black text-white mb-2 font-azo">{project.title}</h3>
                      <p className="text-white/90 mb-4 font-garamond">{project.description}</p>
                      <div className="flex justify-between items-center text-white/80 font-garamond text-sm mb-4">
                        <span>{project.location}</span>
                        <span>{project.year}</span>
                      </div>
                      <Button 
                        variant="secondary" 
                        className="bg-white text-brand-primary hover:bg-white/90 w-full"
                      >
                        View Details
                      </Button>
                    </div>
                  </div>
                </motion.div>
              ))}
            </div>
            <div className="text-center mt-12">
              <Button 
                size="lg"
                className="bg-brand-primary text-white hover:bg-brand-primary/90 font-azo"
              >
                View All Projects
              </Button>
            </div>
          </motion.div>
        </div>
      </section>

      {/* Contact Section */}
      // ... keep existing code (Contact section)

      {/* Footer */}
      // ... keep existing code (Footer section)
    </div>
  );
};

export default Index;
import { NavigationMenu, NavigationMenuContent, NavigationMenuItem, NavigationMenuLink, NavigationMenuList, NavigationMenuTrigger } from "@/components/ui/navigation-menu";
import { cn } from "@/lib/utils";
import { Link } from "react-router-dom";

const MainNav = () => {
  return (
    <NavigationMenu className="hidden md:flex">
      <NavigationMenuList>
        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-white hover:text-white/90">About</NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4 md:w-[500px] md:grid-cols-2 lg:w-[600px]">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/who-we-are"
                  >
                    <div className="text-sm font-medium leading-none">Who We Are</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/faqs"
                  >
                    <div className="text-sm font-medium leading-none">FAQs</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/partners"
                  >
                    <div className="text-sm font-medium leading-none">Partners</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-white hover:text-white/90">What We Do</NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4 md:w-[500px] md:grid-cols-2 lg:w-[600px]">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/projects"
                  >
                    <div className="text-sm font-medium leading-none">Projects</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/services"
                  >
                    <div className="text-sm font-medium leading-none">Services</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <Link to="/blog" className={cn(
            "group inline-flex h-10 w-max items-center justify-center rounded-md px-4 py-2 text-white hover:text-white/90 transition-colors"
          )}>
            Blog
          </Link>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <Link to="/connect" className={cn(
            "group inline-flex h-10 w-max items-center justify-center rounded-md px-4 py-2 text-white hover:text-white/90 transition-colors"
          )}>
            Connect
          </Link>
        </NavigationMenuItem>
      </NavigationMenuList>
    </NavigationMenu>
  );
};

export default MainNav;
Now let's update App.tsx with the new routes:
src/App.tsx
import { Toaster } from "@/components/ui/toaster";
import { Toaster as Sonner } from "@/components/ui/sonner";
import { TooltipProvider } from "@/components/ui/tooltip";
import { QueryClient, QueryClientProvider } from "@tanstack/react-query";
import { BrowserRouter, Routes, Route } from "react-router-dom";
import Index from "./pages/Index";
import WhoWeAre from "./pages/WhoWeAre";
import FAQs from "./pages/FAQs";
import Partners from "./pages/Partners";
import Projects from "./pages/Projects";
import Services from "./pages/Services";
import Blog from "./pages/Blog";
import Connect from "./pages/Connect";

const queryClient = new QueryClient();

const App = () => (
  <QueryClientProvider client={queryClient}>
    <TooltipProvider>
      <Toaster />
      <Sonner />
      <BrowserRouter>
        <Routes>
          <Route path="/" element={<Index />} />
          <Route path="/who-we-are" element={<WhoWeAre />} />
          <Route path="/faqs" element={<FAQs />} />
          <Route path="/partners" element={<Partners />} />
          <Route path="/projects" element={<Projects />} />
          <Route path="/services" element={<Services />} />
          <Route path="/blog" element={<Blog />} />
          <Route path="/connect" element={<Connect />} />
        </Routes>
      </BrowserRouter>
    </TooltipProvider>
  </QueryClientProvider>
);

export default App;
Let's create placeholder pages for each route:
src/pages/WhoWeAre.tsx
import { motion } from "framer-motion";

const WhoWeAre = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">Who We Are</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default WhoWeAre;
src/pages/FAQs.tsx
import { motion } from "framer-motion";

const FAQs = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">FAQs</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default FAQs;
src/pages/Partners.tsx
import { motion } from "framer-motion";

const Partners = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">Partners</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default Partners;
src/pages/Projects.tsx
import { motion } from "framer-motion";

const Projects = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">Projects</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default Projects;
src/pages/Services.tsx
import { motion } from "framer-motion";

const Services = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">Services</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default Services;
src/pages/Blog.tsx
import { motion } from "framer-motion";

const Blog = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">Blog</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default Blog;
src/pages/Connect.tsx
import { motion } from "framer-motion";

const Connect = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-8">Connect</h1>
        <p className="text-xl text-brand-gray/80 font-garamond">Coming soon...</p>
      </motion.div>
    </div>
  );
};

export default Connect;
Now let's update the Index.tsx to include the navigation:
src/pages/Index.tsx
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";
import MainNav from "@/components/MainNav";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div className="w-full h-full bg-gradient-to-r from-brand-primary/90 to-brand-secondary/90" />
        </div>
        <div className="absolute top-0 left-0 right-0 z-50 py-6">
          <div className="container mx-auto px-4 flex justify-between items-center">
            <Link to="/" className="text-white text-2xl font-black">Constructschön</Link>
            <MainNav />
          </div>
        </div>
        // ... keep existing code (hero content)
      </section>

      // ... keep existing code (services section, featured projects, contact section, and footer)
    </div>
  );
};

export default Index;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";
import MainNav from "@/components/MainNav";
import { Link } from "react-router-dom";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div className="w-full h-full bg-gradient-to-r from-brand-primary/90 to-brand-secondary/90" />
        </div>
        <div className="absolute top-0 left-0 right-0 z-50 py-6">
          <div className="container mx-auto px-4 flex justify-between items-center">
            <Link to="/" className="flex items-center">
              <div className="flex items-center">
                <img 
                  src="/lovable-uploads/469e6f4f-f8f6-4af3-9ba6-22c0541305bf.png" 
                  alt="Constructschön Logo" 
                  className="h-12"
                />
                <div className="ml-2 text-white text-xs uppercase tracking-wider">
                  <div>Sustainable Urban Development</div>
                </div>
              </div>
            </Link>
            <MainNav />
          </div>
        </div>
        
        // ... keep existing code (hero content, services section, featured projects, contact section, and footer)
      </section>
    </div>
  );
};

export default Index;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";
import MainNav from "@/components/MainNav";
import { Link } from "react-router-dom";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div className="w-full h-full bg-gradient-to-r from-brand-primary/90 to-brand-secondary/90" />
        </div>
        <div className="absolute top-0 left-0 right-0 z-50 py-6">
          <div className="container mx-auto px-4 flex justify-between items-center">
            <Link to="/" className="flex items-center">
              <div className="flex items-center bg-white/95 rounded-lg px-4 py-2">
                <img 
                  src="/lovable-uploads/469e6f4f-f8f6-4af3-9ba6-22c0541305bf.png" 
                  alt="Constructschön Logo" 
                  className="h-12"
                />
                <div className="ml-2 text-brand-primary text-xs uppercase tracking-wider">
                  <div>Sustainable Urban Development</div>
                </div>
              </div>
            </Link>
            <MainNav />
          </div>
        </div>
        // ... keep existing code (rest of the hero section content)
      </section>

      // ... keep existing code (Services, Featured Projects, Contact sections and Footer)
    </div>
  );
};

export default Index;
import { NavigationMenu, NavigationMenuContent, NavigationMenuItem, NavigationMenuLink, NavigationMenuList, NavigationMenuTrigger } from "@/components/ui/navigation-menu";
import { cn } from "@/lib/utils";
import { Link } from "react-router-dom";

const MainNav = () => {
  return (
    <NavigationMenu className="hidden md:flex">
      <NavigationMenuList>
        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-brand-gray hover:text-brand-primary font-bold">About</NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4 md:w-[500px] md:grid-cols-2 lg:w-[600px]">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/who-we-are"
                  >
                    <div className="text-sm font-medium leading-none">Who We Are</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/faqs"
                  >
                    <div className="text-sm font-medium leading-none">FAQs</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/partners"
                  >
                    <div className="text-sm font-medium leading-none">Partners</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-brand-gray hover:text-brand-primary font-bold">What We Do</NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4 md:w-[500px] md:grid-cols-2 lg:w-[600px]">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/projects"
                  >
                    <div className="text-sm font-medium leading-none">Projects</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/services"
                  >
                    <div className="text-sm font-medium leading-none">Services</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <Link to="/blog" className={cn(
            "group inline-flex h-10 w-max items-center justify-center rounded-md px-4 py-2 text-brand-gray hover:text-brand-primary font-bold transition-colors"
          )}>
            Blog
          </Link>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <Link to="/connect" className={cn(
            "group inline-flex h-10 w-max items-center justify-center rounded-md px-4 py-2 text-brand-gray hover:text-brand-primary font-bold transition-colors"
          )}>
            Connect
          </Link>
        </NavigationMenuItem>
      </NavigationMenuList>
    </NavigationMenu>
  );
};

export default MainNav;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";
import MainNav from "@/components/MainNav";
import { Link } from "react-router-dom";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        // ... keep existing code (hero section background and navigation)
        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
          >
            <h1 className="text-7xl font-black mb-6 text-white font-azo">
              Constructschön
            </h1>
            <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
              A boutique Canadian design-build firm delivering sustainable urban development
            </p>
            <Link to="/projects">
              <Button 
                size="lg" 
                className="bg-white text-brand-primary hover:bg-white/90 font-azo"
              >
                Explore Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      // ... keep existing code (remaining sections)
    </div>
  );
};

export default Index;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";
import MainNav from "@/components/MainNav";
import { Link } from "react-router-dom";

const Index = () => {
  return (
    <div className="min-h-screen">
      // ... keep existing code (Hero and Services sections)

      {/* Contact Section */}
      <section className="py-24 bg-brand-primary text-white">
        <div className="container mx-auto px-4 text-center">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black mb-8 font-azo">Let's Build Together</h2>
            <p className="text-white/90 mb-8 max-w-2xl mx-auto font-garamond text-lg">
              Ready to start your next construction project? Contact us today for a consultation.
            </p>
            <Link to="/connect">
              <Button 
                size="lg" 
                className="bg-white text-brand-primary hover:bg-white/90 font-azo"
              >
                Get in Touch
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      // ... keep existing code (Footer section)
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Card, CardContent, CardDescription, CardHeader, CardTitle } from "@/components/ui/card";
import { Link } from "react-router-dom";

const projects = [
  {
    id: 1,
    title: "Modern Office Complex",
    description: "A state-of-the-art office building featuring sustainable design and smart technology integration.",
    image: "/lovable-uploads/038e8f10-8c3c-4240-b9e5-41f0ebb477b3.png",
    category: "Commercial"
  },
  {
    id: 2,
    title: "Luxury Residential Tower",
    description: "High-end residential development with premium amenities and panoramic city views.",
    image: "/lovable-uploads/469e6f4f-f8f6-4af3-9ba6-22c0541305bf.png",
    category: "Residential"
  },
  {
    id: 3,
    title: "Shopping Mall Renovation",
    description: "Complete renovation and modernization of an existing shopping complex.",
    image: "/lovable-uploads/4def6ecd-67f4-4c43-b547-08ebac399e34.png",
    category: "Commercial"
  },
  {
    id: 4,
    title: "Healthcare Facility",
    description: "Modern medical facility designed for optimal patient care and staff efficiency.",
    image: "/lovable-uploads/c9e1a219-dd4c-4b54-bfe1-78a00641fe2c.png",
    category: "Healthcare"
  }
];

const Projects = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-4">Our Projects</h1>
        <p className="text-xl text-brand-gray/80 font-garamond mb-12">
          Explore our portfolio of successful construction projects across various sectors.
        </p>

        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          {projects.map((project) => (
            <motion.div
              key={project.id}
              initial={{ opacity: 0, y: 20 }}
              animate={{ opacity: 1, y: 0 }}
              transition={{ duration: 0.5, delay: project.id * 0.1 }}
            >
              <Card className="h-full hover:shadow-lg transition-shadow duration-300">
                <div className="aspect-video relative overflow-hidden rounded-t-lg">
                  <img
                    src={project.image}
                    alt={project.title}
                    className="object-cover w-full h-full transform hover:scale-105 transition-transform duration-300"
                  />
                </div>
                <CardHeader>
                  <div className="flex justify-between items-center mb-2">
                    <span className="text-sm font-medium text-brand-primary">
                      {project.category}
                    </span>
                  </div>
                  <CardTitle className="text-xl text-brand-gray">
                    {project.title}
                  </CardTitle>
                  <CardDescription className="text-brand-gray/70 font-garamond">
                    {project.description}
                  </CardDescription>
                </CardHeader>
                <CardContent>
                  <Link 
                    to={`/connect`} 
                    className="text-brand-primary hover:text-brand-primary/80 font-medium inline-flex items-center"
                  >
                    Learn More
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      className="h-4 w-4 ml-1"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        strokeLinecap="round"
                        strokeLinejoin="round"
                        strokeWidth={2}
                        d="M9 5l7 7-7 7"
                      />
                    </svg>
                  </Link>
                </CardContent>
              </Card>
            </motion.div>
          ))}
        </div>
      </motion.div>
    </div>
  );
};

export default Projects;
import { motion } from "framer-motion";
import { Card, CardContent, CardDescription, CardHeader, CardTitle } from "@/components/ui/card";
import { Link } from "react-router-dom";

const services = [
  {
    id: 1,
    title: "Construction Management",
    description: "Expert oversight of construction projects from planning to completion, ensuring quality, timeline, and budget compliance.",
    icon: (
      <svg xmlns="http://www.w3.org/2000/svg" className="h-8 w-8 text-brand-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M19 21V5a2 2 0 00-2-2H7a2 2 0 00-2 2v16m14 0h2m-2 0h-5m-9 0H3m2 0h5M9 7h1m-1 4h1m4-4h1m-1 4h1m-5 10v-5a1 1 0 011-1h2a1 1 0 011 1v5m-4 0h4" />
      </svg>
    ),
    category: "Management"
  },
  {
    id: 2,
    title: "Architectural Design",
    description: "Innovative architectural solutions that blend aesthetics with functionality, creating spaces that inspire and endure.",
    icon: (
      <svg xmlns="http://www.w3.org/2000/svg" className="h-8 w-8 text-brand-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 20l-5.447-2.724A1 1 0 013 16.382V5.618a1 1 0 011.447-.894L9 7m0 13l6-3m-6 3V7m6 10l4.553 2.276A1 1 0 0021 18.382V7.618a1 1 0 00-.553-.894L15 4m0 13V4m0 0L9 7" />
      </svg>
    ),
    category: "Design"
  },
  {
    id: 3,
    title: "Sustainable Building",
    description: "Green construction practices and sustainable solutions that minimize environmental impact while maximizing efficiency.",
    icon: (
      <svg xmlns="http://www.w3.org/2000/svg" className="h-8 w-8 text-brand-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M3.055 11H5a2 2 0 012 2v1a2 2 0 002 2 2 2 0 012 2v2.945M8 3.935V5.5A2.5 2.5 0 0010.5 8h.5a2 2 0 012 2 2 2 0 104 0 2 2 0 012-2h1.064M15 20.488V18a2 2 0 012-2h3.064M21 12a9 9 0 11-18 0 9 9 0 0118 0z" />
      </svg>
    ),
    category: "Sustainability"
  },
  {
    id: 4,
    title: "Renovation & Restoration",
    description: "Expert restoration and renovation services that preserve historical value while incorporating modern amenities.",
    icon: (
      <svg xmlns="http://www.w3.org/2000/svg" className="h-8 w-8 text-brand-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M12 6V4m0 2a2 2 0 100 4m0-4a2 2 0 110 4m-6 8a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4m6 6v10m6-2a2 2 0 100-4m0 4a2 2 0 110-4m0 4v2m0-6V4" />
      </svg>
    ),
    category: "Renovation"
  },
  {
    id: 5,
    title: "Interior Design",
    description: "Comprehensive interior design services that transform spaces into functional and aesthetically pleasing environments.",
    icon: (
      <svg xmlns="http://www.w3.org/2000/svg" className="h-8 w-8 text-brand-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M7 21a4 4 0 01-4-4V5a2 2 0 012-2h4a2 2 0 012 2v12a4 4 0 01-4 4zm0 0h12a2 2 0 002-2v-4a2 2 0 00-2-2h-2.343M11 7.343l1.657-1.657a2 2 0 012.828 0l2.829 2.829a2 2 0 010 2.828l-8.486 8.485M7 17h.01" />
      </svg>
    ),
    category: "Design"
  },
  {
    id: 6,
    title: "Project Consulting",
    description: "Strategic consulting services to help clients make informed decisions throughout their construction journey.",
    icon: (
      <svg xmlns="http://www.w3.org/2000/svg" className="h-8 w-8 text-brand-primary" fill="none" viewBox="0 0 24 24" stroke="currentColor">
        <path strokeLinecap="round" strokeLinejoin="round" strokeWidth={2} d="M9 5H7a2 2 0 00-2 2v12a2 2 0 002 2h10a2 2 0 002-2V7a2 2 0 00-2-2h-2M9 5a2 2 0 002 2h2a2 2 0 002-2M9 5a2 2 0 012-2h2a2 2 0 012 2m-3 7h3m-3 4h3m-6-4h.01M9 16h.01" />
      </svg>
    ),
    category: "Consulting"
  }
];

const Services = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-4">Our Services</h1>
        <p className="text-xl text-brand-gray/80 font-garamond mb-12">
          Comprehensive construction and design services tailored to your needs.
        </p>

        <div className="grid grid-cols-1 md:grid-cols-2 lg:grid-cols-3 gap-8">
          {services.map((service) => (
            <motion.div
              key={service.id}
              initial={{ opacity: 0, y: 20 }}
              animate={{ opacity: 1, y: 0 }}
              transition={{ duration: 0.5, delay: service.id * 0.1 }}
            >
              <Card className="h-full hover:shadow-lg transition-shadow duration-300">
                <CardHeader>
                  <div className="flex justify-between items-center mb-4">
                    <div className="p-2 bg-brand-primary/10 rounded-lg">
                      {service.icon}
                    </div>
                    <span className="text-sm font-medium text-brand-primary">
                      {service.category}
                    </span>
                  </div>
                  <CardTitle className="text-xl text-brand-gray">
                    {service.title}
                  </CardTitle>
                  <CardDescription className="text-brand-gray/70 font-garamond">
                    {service.description}
                  </CardDescription>
                </CardHeader>
                <CardContent>
                  <Link 
                    to="/connect" 
                    className="text-brand-primary hover:text-brand-primary/80 font-medium inline-flex items-center"
                  >
                    Get Started
                    <svg
                      xmlns="http://www.w3.org/2000/svg"
                      className="h-4 w-4 ml-1"
                      fill="none"
                      viewBox="0 0 24 24"
                      stroke="currentColor"
                    >
                      <path
                        strokeLinecap="round"
                        strokeLinejoin="round"
                        strokeWidth={2}
                        d="M9 5l7 7-7 7"
                      />
                    </svg>
                  </Link>
                </CardContent>
              </Card>
            </motion.div>
          ))}
        </div>
      </motion.div>
    </div>
  );
};

export default Services;
import { NavigationMenu, NavigationMenuContent, NavigationMenuItem, NavigationMenuLink, NavigationMenuList, NavigationMenuTrigger } from "@/components/ui/navigation-menu";
import { cn } from "@/lib/utils";
import { Link } from "react-router-dom";

const MainNav = () => {
  return (
    <NavigationMenu className="hidden md:flex">
      <NavigationMenuList>
        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-brand-gray hover:text-brand-primary font-bold">About</NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4 md:w-[500px] md:grid-cols-2 lg:w-[600px]">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/who-we-are"
                  >
                    <div className="text-sm font-medium leading-none">Who We Are</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/faqs"
                  >
                    <div className="text-sm font-medium leading-none">FAQs</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/partners"
                  >
                    <div className="text-sm font-medium leading-none">Partners</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-brand-gray hover:text-brand-primary font-bold">What We Do</NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4 md:w-[500px] md:grid-cols-2 lg:w-[600px]">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/projects"
                  >
                    <div className="text-sm font-medium leading-none">Projects</div>
                  </Link>
                </NavigationMenuLink>
              </li>
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/services"
                  >
                    <div className="text-sm font-medium leading-none">Services</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-brand-gray hover:text-brand-primary font-bold">
            Blog
          </NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/blog"
                  >
                    <div className="text-sm font-medium leading-none">View All Posts</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>

        <NavigationMenuItem>
          <NavigationMenuTrigger className="text-brand-gray hover:text-brand-primary font-bold">
            Connect
          </NavigationMenuTrigger>
          <NavigationMenuContent>
            <ul className="grid w-[400px] gap-3 p-4">
              <li>
                <NavigationMenuLink asChild>
                  <Link
                    className="block select-none space-y-1 rounded-md p-3 leading-none no-underline outline-none transition-colors hover:bg-accent hover:text-accent-foreground focus:bg-accent focus:text-accent-foreground"
                    to="/connect"
                  >
                    <div className="text-sm font-medium leading-none">Get in Touch</div>
                  </Link>
                </NavigationMenuLink>
              </li>
            </ul>
          </NavigationMenuContent>
        </NavigationMenuItem>
      </NavigationMenuList>
    </NavigationMenu>
  );
};

export default MainNav;
import { Button } from "@/components/ui/button";
import { Card, CardContent } from "@/components/ui/card";
import { motion } from "framer-motion";
import MainNav from "@/components/MainNav";
import { Link } from "react-router-dom";

const Index = () => {
  return (
    <div className="min-h-screen relative">
      {/* Background Image */}
      <div className="fixed inset-0 z-0">
        <div 
          className="w-full h-full bg-cover bg-center bg-no-repeat opacity-10"
          style={{ 
            backgroundImage: 'url("/lovable-uploads/17f43e8a-9b7e-4b6d-8bc9-b4f24f4e33ea.png")',
            backgroundPosition: 'center 40%'
          }}
        />
      </div>

      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div className="w-full h-full bg-gradient-to-r from-brand-primary/90 to-brand-secondary/90" />
        </div>
        // ... keep existing code (navigation section)

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
          >
            <h1 className="text-7xl font-black mb-6 text-white font-azo">
              Constructschön
            </h1>
            <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
              Sustainable Urban Development
            </p>
            <Link to="/projects">
              <Button 
                size="lg" 
                className="bg-white text-brand-primary hover:bg-white/90 font-azo"
              >
                Explore Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      // ... keep existing code (Services Section, Featured Projects, Contact Section, and Footer)
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-4 py-6">
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          {/* Background Image behind title */}
          <div className="absolute inset-0 -z-10">
            <div 
              className="w-full h-full bg-cover bg-center bg-no-repeat opacity-10"
              style={{ 
                backgroundImage: 'url("/lovable-uploads/17f43e8a-9b7e-4b6d-8bc9-b4f24f4e33ea.png")',
                backgroundPosition: 'center 40%'
              }}
            />
          </div>
          
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="relative"
          >
            <h1 className="text-6xl font-black text-white mb-4">
              Constructschön
            </h1>
            <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
              Sustainable Urban Development
            </p>
            <Link to="/projects">
              <Button 
                variant="outline" 
                className="bg-white/10 text-white border-white hover:bg-white/20"
              >
                View Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      <section className="py-24 bg-white">
        // ... keep existing code (services section content)
      </section>
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-4 py-6">
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="relative"
          >
            {/* Background Image behind title and tagline */}
            <div className="absolute inset-0 -z-10">
              <div 
                className="w-full h-full bg-cover bg-center bg-no-repeat opacity-10"
                style={{ 
                  backgroundImage: 'url("/lovable-uploads/17f43e8a-9b7e-4b6d-8bc9-b4f24f4e33ea.png")',
                  backgroundPosition: 'center 20%'
                }}
              />
            </div>
            
            <div className="relative py-12">
              <h1 className="text-6xl font-black text-white mb-4">
                Constructschön
              </h1>
              <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
                A boutique Canadian design build firm delivering sustainable urban development
              </p>
            </div>
            
            <Link to="/projects">
              <Button 
                variant="outline" 
                className="bg-white/10 text-white border-white hover:bg-white/20"
              >
                View Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      <section className="py-24 bg-white">
        <div className="container mx-auto px-4">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black text-center mb-16 text-brand-gray font-azo">
              Our Expertise
            </h2>
            <div className="grid md:grid-cols-3 gap-8">
              {[
                {
                  title: "Project Development",
                  description: "Comprehensive project management and development services for sustainable urban growth."
                },
                {
                  title: "Construction Management",
                  description: "Expert construction management with a focus on efficiency and sustainability."
                },
                {
                  title: "Sustainable Design",
                  description: "Innovative design solutions that prioritize environmental responsibility."
                }
              ].map((service, index) => (
                <motion.div
                  key={index}
                  initial={{ opacity: 0, y: 20 }}
                  whileInView={{ opacity: 1, y: 0 }}
                  transition={{ duration: 0.6, delay: index * 0.2 }}
                  viewport={{ once: true }}
                >
                  <Card className="hover:shadow-lg transition-all duration-300 border-none bg-gray-50">
                    <CardContent className="pt-6">
                      <h3 className="text-xl font-black mb-4 text-brand-primary font-azo">{service.title}</h3>
                      <p className="text-brand-gray font-garamond">{service.description}</p>
                    </CardContent>
                  </Card>
                </motion.div>
              ))}
            </div>
          </motion.div>
        </div>
      </section>
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-4 py-6 flex justify-end">
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="relative"
          >
            {/* Background Image behind title and tagline */}
            <div className="absolute inset-0 -z-10">
              <div 
                className="w-full h-full bg-cover bg-center bg-no-repeat opacity-10"
                style={{ 
                  backgroundImage: 'url("/lovable-uploads/17f43e8a-9b7e-4b6d-8bc9-b4f24f4e33ea.png")',
                  backgroundPosition: 'center 20%'
                }}
              />
            </div>
            
            <div className="relative py-12">
              <h1 className="text-6xl font-black text-white mb-4">
                Constructschön
              </h1>
              <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
                A boutique Canadian design build firm delivering sustainable urban development
              </p>
            </div>
            
            <Link to="/projects">
              <Button 
                variant="outline" 
                className="bg-white/10 text-white border-white hover:bg-white/20"
              >
                View Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      // ... keep existing code (expertise section)
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Tagline */}
        <div className="absolute top-6 left-4 z-20 text-white font-azo">
          [ DESIGNED & PREPARED FOR ]
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-4 py-6 flex justify-end">
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="relative"
          >
            {/* Background Image behind title and tagline */}
            <div className="absolute inset-0 -z-10">
              <div 
                className="w-full h-full bg-cover bg-center bg-no-repeat opacity-10"
                style={{ 
                  backgroundImage: 'url("/lovable-uploads/17f43e8a-9b7e-4b6d-8bc9-b4f24f4e33ea.png")',
                  backgroundPosition: 'center 20%'
                }}
              />
            </div>
            
            <div className="relative py-12">
              <h1 className="text-6xl font-black text-white mb-4">
                Constructschön
              </h1>
              <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
                A boutique Canadian design build firm delivering sustainable urban development
              </p>
            </div>
            
            <Link to="/projects">
              <Button 
                variant="outline" 
                className="bg-white/10 text-white border-white hover:bg-white/20"
              >
                View Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      // ... keep existing code (Our Expertise section)
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-4 py-6 flex justify-end">
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="relative"
          >
            {/* Background Image behind title and tagline */}
            <div className="absolute inset-0 -z-10">
              <div 
                className="w-full h-full bg-cover bg-center bg-no-repeat opacity-10"
                style={{ 
                  backgroundImage: 'url("/lovable-uploads/17f43e8a-9b7e-4b6d-8bc9-b4f24f4e33ea.png")',
                  backgroundPosition: 'center 20%'
                }}
              />
            </div>
            
            <div className="relative py-12">
              <h1 className="text-6xl font-black text-white mb-4">
                Constructschön
              </h1>
              <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
                A boutique Canadian design build firm delivering sustainable urban development
              </p>
            </div>
            
            <Link to="/projects">
              <Button 
                variant="outline" 
                className="bg-white/10 text-white border-white hover:bg-white/20"
              >
                View Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      // ... keep existing code (expertise section)
    </div>
  );
};

export default Index;
mport { motion } from "framer-motion";
import {
  Accordion,
  AccordionContent,
  AccordionItem,
  AccordionTrigger,
} from "@/components/ui/accordion";

const faqs = [
  {
    question: "What services do you offer?",
    answer: "We offer a comprehensive range of construction and design services including Construction Management, Architectural Design, Sustainable Building, Renovation & Restoration, Interior Design, and Project Consulting. Each service is tailored to meet our clients' specific needs and requirements."
  },
  {
    question: "How long has your company been in business?",
    answer: "Our company has been a trusted name in the construction industry for over two decades, delivering exceptional results and building lasting relationships with our clients throughout our journey."
  },
  {
    question: "Do you handle both residential and commercial projects?",
    answer: "Yes, we have extensive experience in both residential and commercial construction. Our portfolio includes luxury homes, office buildings, retail spaces, healthcare facilities, and more."
  },
  {
    question: "What is your approach to sustainable construction?",
    answer: "Sustainability is at the core of our construction practices. We implement eco-friendly materials, energy-efficient systems, and green building techniques while adhering to LEED certification standards when applicable."
  },
  {
    question: "How do you ensure project quality and safety?",
    answer: "We maintain rigorous quality control processes and safety protocols throughout all our projects. Our team follows industry best practices, conducts regular inspections, and ensures compliance with all relevant building codes and safety regulations."
  },
  {
    question: "What is your typical project timeline?",
    answer: "Project timelines vary depending on scope and complexity. During initial consultations, we provide detailed project schedules and maintain transparent communication throughout the construction process to ensure timely completion."
  },
  {
    question: "Do you provide warranties for your work?",
    answer: "Yes, we stand behind our work with comprehensive warranties. The specific terms and duration of warranties vary by project type and materials used, which we discuss in detail during the contract phase."
  },
  {
    question: "How do you handle project budgeting and costs?",
    answer: "We work closely with clients to establish clear budgets early in the project planning phase. Our transparent pricing approach includes detailed cost breakdowns, and we maintain regular communication about any potential budget impacts throughout the project."
  }
];

const FAQs = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-24"
      >
        <h1 className="text-4xl font-black text-brand-gray mb-4">
          Frequently Asked Questions
        </h1>
        <p className="text-xl text-brand-gray/80 font-garamond mb-12">
          Find answers to common questions about our services and processes.
        </p>

        <div className="max-w-3xl mx-auto">
          <Accordion type="single" collapsible className="space-y-4">
            {faqs.map((faq, index) => (
              <AccordionItem
                key={index}
                value={`item-${index}`}
                className="bg-white rounded-lg border border-gray-200 px-4"
              >
                <AccordionTrigger className="text-lg font-medium text-brand-gray hover:no-underline">
                  {faq.question}
                </AccordionTrigger>
                <AccordionContent className="text-brand-gray/80 font-garamond text-lg">
                  {faq.answer}
                </AccordionContent>
              </AccordionItem>
            ))}
          </Accordion>
        </div>
      </motion.div>
    </div>
  );
};

export default FAQs;
import { Toaster } from "@/components/ui/toaster";
import { Toaster as Sonner } from "@/components/ui/sonner";
import { TooltipProvider } from "@/components/ui/tooltip";
import { QueryClient, QueryClientProvider } from "@tanstack/react-query";
import { BrowserRouter, Routes, Route } from "react-router-dom";
import Index from "./pages/Index";
import WhoWeAre from "./pages/WhoWeAre";
import FAQs from "./pages/FAQs";
import Partners from "./pages/Partners";
import Projects from "./pages/Projects";
import Services from "./pages/Services";
import Blog from "./pages/Blog";
import Connect from "./pages/Connect";

const queryClient = new QueryClient();

const App = () => {
  return (
    <QueryClientProvider client={queryClient}>
      <TooltipProvider>
        <BrowserRouter>
          <Toaster />
          <Sonner />
          <Routes>
            <Route path="/" element={<Index />} />
            <Route path="/who-we-are" element={<WhoWeAre />} />
            <Route path="/faqs" element={<FAQs />} />
            <Route path="/partners" element={<Partners />} />
            <Route path="/projects" element={<Projects />} />
            <Route path="/services" element={<Services />} />
            <Route path="/blog" element={<Blog />} />
            <Route path="/connect" element={<Connect />} />
          </Routes>
        </BrowserRouter>
      </TooltipProvider>
    </QueryClientProvider>
  );
};

export default App;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-4 py-6 flex justify-end">
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="relative"
          >
            <div className="relative py-12">
              <h1 className="text-6xl font-black text-white mb-4">
                Constructschön
              </h1>
              <p className="text-xl mb-8 text-white/90 max-w-2xl mx-auto font-garamond">
                A boutique Canadian design build firm delivering sustainable urban development
              </p>
            </div>
            
            <Link to="/projects">
              <Button 
                variant="outline" 
                className="bg-white/10 text-white border-white hover:bg-white/20"
              >
                View Our Projects
              </Button>
            </Link>
          </motion.div>
        </div>
      </section>

      <section className="py-24 bg-white">
        <div className="container mx-auto px-4">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
          >
            <h2 className="text-4xl font-black text-center mb-16 text-brand-gray font-azo">
              Our Expertise
            </h2>
            <div className="grid md:grid-cols-3 gap-8">
              {[
                {
                  title: "Project Development",
                  description: "Comprehensive project management and development services for sustainable urban growth."
                },
                {
                  title: "Construction Management",
                  description: "Expert construction management with a focus on efficiency and sustainability."
                },
                {
                  title: "Sustainable Design",
                  description: "Innovative design solutions that prioritize environmental responsibility."
                }
              ].map((service, index) => (
                <motion.div
                  key={index}
                  initial={{ opacity: 0, y: 20 }}
                  whileInView={{ opacity: 1, y: 0 }}
                  transition={{ duration: 0.6, delay: index * 0.2 }}
                  viewport={{ once: true }}
                >
                  <Card className="hover:shadow-lg transition-all duration-300 border-none bg-gray-50">
                    <CardContent className="pt-6">
                      <h3 className="text-xl font-black mb-4 text-brand-primary font-azo">{service.title}</h3>
                      <p className="text-brand-gray font-garamond">{service.description}</p>
                    </CardContent>
                  </Card>
                </motion.div>
              ))}
            </div>
          </motion.div>
        </div>
      </section>
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";

const WhoWeAre = () => {
  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-12 md:py-24"
      >
        {/* Hero Section */}
        <div className="mb-16 text-center">
          <h1 className="text-4xl md:text-5xl font-black text-brand-gray mb-6">Who We Are</h1>
          <p className="text-xl text-brand-gray/80 font-garamond max-w-2xl mx-auto">
            We are a passionate team dedicated to creating innovative solutions that make a difference in people's lives.
          </p>
        </div>

        {/* Mission & Vision */}
        <div className="grid md:grid-cols-2 gap-12 mb-16">
          <motion.div
            initial={{ x: -50, opacity: 0 }}
            animate={{ x: 0, opacity: 1 }}
            transition={{ delay: 0.2 }}
            className="bg-white p-8 rounded-lg shadow-lg"
          >
            <h2 className="text-2xl font-black text-brand-primary mb-4">Our Mission</h2>
            <p className="font-garamond text-lg text-brand-gray/80">
              To deliver exceptional value through innovative solutions, fostering growth and positive change in every project we undertake.
            </p>
          </motion.div>

          <motion.div
            initial={{ x: 50, opacity: 0 }}
            animate={{ x: 0, opacity: 1 }}
            transition={{ delay: 0.4 }}
            className="bg-white p-8 rounded-lg shadow-lg"
          >
            <h2 className="text-2xl font-black text-brand-secondary mb-4">Our Vision</h2>
            <p className="font-garamond text-lg text-brand-gray/80">
              To be recognized as a leading force in creating meaningful impact through technology and innovation.
            </p>
          </motion.div>
        </div>

        {/* Values Section */}
        <div className="mb-16">
          <h2 className="text-3xl font-black text-brand-gray text-center mb-8">Our Values</h2>
          <div className="grid md:grid-cols-3 gap-8">
            {[
              {
                title: "Innovation",
                description: "We embrace creative thinking and cutting-edge solutions."
              },
              {
                title: "Integrity",
                description: "We maintain the highest standards of honesty and ethics."
              },
              {
                title: "Impact",
                description: "We strive to make a positive difference in everything we do."
              }
            ].map((value, index) => (
              <motion.div
                key={value.title}
                initial={{ y: 50, opacity: 0 }}
                animate={{ y: 0, opacity: 1 }}
                transition={{ delay: 0.2 * (index + 3) }}
                className="bg-white p-6 rounded-lg shadow-lg text-center"
              >
                <h3 className="text-xl font-black text-brand-coral mb-3">{value.title}</h3>
                <p className="font-garamond text-brand-gray/80">{value.description}</p>
              </motion.div>
            ))}
          </div>
        </div>

        {/* CTA Section */}
        <motion.div
          initial={{ y: 50, opacity: 0 }}
          animate={{ y: 0, opacity: 1 }}
          transition={{ delay: 1 }}
          className="text-center"
        >
          <h2 className="text-2xl font-black text-brand-gray mb-6">Ready to Work Together?</h2>
          <Button asChild className="bg-brand-primary hover:bg-brand-primary/90">
            <Link to="/connect">Get in Touch</Link>
          </Button>
        </motion.div>
      </motion.div>
    </div>
  );
};

export default WhoWeAre;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Input } from "@/components/ui/input";
import { Textarea } from "@/components/ui/textarea";
import { useForm } from "react-hook-form";
import { toast } from "sonner";
import { Mail, Phone, MapPin } from "lucide-react";

interface ContactFormData {
  name: string;
  email: string;
  subject: string;
  message: string;
}

const Connect = () => {
  const { register, handleSubmit, reset, formState: { errors } } = useForm<ContactFormData>();

  const onSubmit = (data: ContactFormData) => {
    console.log("Form submitted:", data);
    toast.success("Thank you for your message! We'll get back to you soon.");
    reset();
  };

  return (
    <div className="min-h-screen bg-white">
      <motion.div
        initial={{ opacity: 0 }}
        animate={{ opacity: 1 }}
        transition={{ duration: 0.5 }}
        className="container mx-auto px-4 py-12 md:py-24"
      >
        {/* Hero Section */}
        <div className="text-center mb-16">
          <h1 className="text-4xl md:text-5xl font-black text-brand-gray mb-6">Let's Connect</h1>
          <p className="text-xl text-brand-gray/80 font-garamond max-w-2xl mx-auto">
            Have a question or want to work together? We'd love to hear from you.
          </p>
        </div>

        <div className="grid md:grid-cols-2 gap-12 max-w-6xl mx-auto">
          {/* Contact Information */}
          <motion.div
            initial={{ x: -50, opacity: 0 }}
            animate={{ x: 0, opacity: 1 }}
            transition={{ delay: 0.2 }}
            className="space-y-8"
          >
            <h2 className="text-2xl font-black text-brand-primary mb-6">Contact Information</h2>
            
            <div className="space-y-6">
              <div className="flex items-start gap-4">
                <Mail className="w-6 h-6 text-brand-coral mt-1" />
                <div>
                  <h3 className="font-black text-brand-gray">Email Us</h3>
                  <p className="font-garamond text-brand-gray/80">hello@company.com</p>
                </div>
              </div>

              <div className="flex items-start gap-4">
                <Phone className="w-6 h-6 text-brand-coral mt-1" />
                <div>
                  <h3 className="font-black text-brand-gray">Call Us</h3>
                  <p className="font-garamond text-brand-gray/80">+1 (555) 123-4567</p>
                </div>
              </div>

              <div className="flex items-start gap-4">
                <MapPin className="w-6 h-6 text-brand-coral mt-1" />
                <div>
                  <h3 className="font-black text-brand-gray">Visit Us</h3>
                  <p className="font-garamond text-brand-gray/80">
                    123 Innovation Street<br />
                    Tech City, TC 12345
                  </p>
                </div>
              </div>
            </div>
          </motion.div>

          {/* Contact Form */}
          <motion.div
            initial={{ x: 50, opacity: 0 }}
            animate={{ x: 0, opacity: 1 }}
            transition={{ delay: 0.4 }}
            className="bg-white p-8 rounded-lg shadow-lg"
          >
            <form onSubmit={handleSubmit(onSubmit)} className="space-y-6">
              <div>
                <Input
                  placeholder="Your Name"
                  {...register("name", { required: "Name is required" })}
                  className={errors.name ? "border-red-500" : ""}
                />
                {errors.name && (
                  <p className="text-red-500 text-sm mt-1">{errors.name.message}</p>
                )}
              </div>

              <div>
                <Input
                  type="email"
                  placeholder="Your Email"
                  {...register("email", {
                    required: "Email is required",
                    pattern: {
                      value: /^[A-Z0-9._%+-]+@[A-Z0-9.-]+\.[A-Z]{2,}$/i,
                      message: "Invalid email address"
                    }
                  })}
                  className={errors.email ? "border-red-500" : ""}
                />
                {errors.email && (
                  <p className="text-red-500 text-sm mt-1">{errors.email.message}</p>
                )}
              </div>

              <div>
                <Input
                  placeholder="Subject"
                  {...register("subject", { required: "Subject is required" })}
                  className={errors.subject ? "border-red-500" : ""}
                />
                {errors.subject && (
                  <p className="text-red-500 text-sm mt-1">{errors.subject.message}</p>
                )}
              </div>

              <div>
                <Textarea
                  placeholder="Your Message"
                  {...register("message", { required: "Message is required" })}
                  className={`min-h-[150px] ${errors.message ? "border-red-500" : ""}`}
                />
                {errors.message && (
                  <p className="text-red-500 text-sm mt-1">{errors.message.message}</p>
                )}
              </div>

              <Button
                type="submit"
                className="w-full bg-brand-primary hover:bg-brand-primary/90"
              >
                Send Message
              </Button>
            </form>
          </motion.div>
        </div>
      </motion.div>
    </div>
  );
};

export default Connect;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";
import { ArrowRight, Building2, Leaf, Users } from "lucide-react";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-8 py-8 flex justify-between items-center">
            {/* Logo */}
            <Link to="/" className="flex items-center">
              <img 
                src="/lovable-uploads/8f788fc1-efc0-4739-ab68-0cbf52795cbd.png" 
                alt="Logo" 
                className="h-16 w-auto [filter:brightness(0)]"
              />
            </Link>
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="max-w-3xl mx-auto"
          >
            <h1 className="text-7xl font-black text-white mb-6 leading-tight">
              Constructschön
            </h1>
            <p className="text-2xl mb-12 text-white/90 max-w-2xl mx-auto font-garamond leading-relaxed">
              A boutique Canadian design build firm delivering sustainable urban development
            </p>
            <div className="flex gap-4 justify-center">
              <Link to="/projects">
                <Button 
                  size="lg"
                  variant="outline" 
                  className="bg-white text-brand-primary border-white hover:bg-white/90"
                >
                  View Our Projects
                </Button>
              </Link>
              <Link to="/connect">
                <Button 
                  size="lg"
                  className="bg-brand-coral text-white hover:bg-brand-coral/90 border-none"
                >
                  Get in Touch <ArrowRight className="ml-2 h-4 w-4" />
                </Button>
              </Link>
            </div>
          </motion.div>
        </div>
      </section>

      {/* Values Section */}
      <section className="py-24 bg-white">
        <div className="container mx-auto px-4">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            whileInView={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.6 }}
            viewport={{ once: true }}
            className="text-center mb-16"
          >
            <h2 className="text-4xl font-black mb-6 text-brand-gray">
              Our Core Values
            </h2>
            <p className="text-xl text-brand-gray/80 max-w-2xl mx-auto font-garamond">
              We believe in creating developments that stand the test of time while respecting our environment and communities.
            </p>
          </motion.div>

          <div className="grid md:grid-cols-3 gap-8">
            {[
              {
                icon: Building2,
                title: "Quality Construction",
                description: "We use premium materials and innovative techniques to ensure lasting quality in every project."
              },
              {
                icon: Leaf,
                title: "Sustainability First",
                description: "Environmental responsibility is at the core of our design and construction processes."
              },
              {
                icon: Users,
                title: "Community Focus",
                description: "We create spaces that foster connection and enhance the lives of community members."
              }
            ].map((value, index) => (
              <motion.div
                key={index}
                initial={{ opacity: 0, y: 20 }}
                whileInView={{ opacity: 1, y: 0 }}
                transition={{ duration: 0.6, delay: index * 0.2 }}
                viewport={{ once: true }}
              >
                <Card className="hover:shadow-lg transition-all duration-300 border-none bg-gray-50">
                  <CardContent className="pt-6 text-center">
                    <div className="mb-4 flex justify-center">
                      <value.icon className="h-12 w-12 text-brand-primary" />
                    </div>
                    <h3 className="text-xl font-black mb-4 text-brand-primary">{value.title}</h3>
                    <p className="text-brand-gray font-garamond">{value.description}</p>
                  </CardContent>
                </Card>
              </motion.div>
            ))}
          </div>
        </div>
      </section>
    </div>
  );
};

export default Index;
import { motion } from "framer-motion";
import { Button } from "@/components/ui/button";
import { Link } from "react-router-dom";
import MainNav from "@/components/MainNav";
import { Card, CardContent } from "@/components/ui/card";
import { ArrowRight, Building2, Leaf, Users } from "lucide-react";

const Index = () => {
  return (
    <div className="min-h-screen">
      {/* Hero Section with Navigation */}
      <section className="relative h-screen flex items-center justify-center overflow-hidden">
        <div className="absolute inset-0 z-0">
          <div
            className="w-full h-full bg-gradient-to-b from-brand-primary/90 to-brand-secondary/90"
            style={{
              backgroundImage:
                "linear-gradient(to bottom, rgba(198, 0, 126, 0.9), rgba(0, 155, 119, 0.9))",
            }}
          />
        </div>

        {/* Navigation */}
        <div className="absolute top-0 left-0 right-0 z-20">
          <div className="container mx-auto px-8 py-8 flex justify-between items-center">
            {/* Logo */}
            <Link to="/" className="flex items-center">
              <img 
                src="/lovable-uploads/8f788fc1-efc0-4739-ab68-0cbf52795cbd.png" 
                alt="Logo" 
                className="h-16 w-auto [filter:brightness(0)]"
              />
            </Link>
            <MainNav />
          </div>
        </div>

        <div className="container mx-auto px-4 text-center relative z-10">
          <motion.div
            initial={{ opacity: 0, y: 20 }}
            animate={{ opacity: 1, y: 0 }}
            transition={{ duration: 0.8 }}
            className="max-w-3xl mx-auto"
          >
            <h1 className="text-7xl font-black text-white mb-6 leading-tight">
              Constructschön
            </h1>
            <p className="text-2xl mb-12 text-white/90 max-w-2xl mx-auto font-garamond leading-relaxed">
              A boutique Canadian design build firm delivering sustainable urban development
            </p>
            <div className="flex gap-4 justify-center">
              <Link to="/projects">
                <Button 
                  size="lg"
                  variant="outline" 
                  className="bg-white text-brand-primary border-white hover:bg-white/90"
                >
                  View Our Projects
                </Button>
              </Link>
              <Link to="/connect">
                <Button 
                  size="lg"
                  className="bg-brand-secondary text-white hover:bg-brand-secondary/90 border-none"
                >
                  Get in Touch <ArrowRight className="ml-2 h-4 w-4" />
                </Button>
              </Link>
            </div>
          </motion.div>
        </div>
      </section>

      {/* Values Section */}
      // ... keep existing code (Values section with cards)
    </div>
  );
};

export default Index;
