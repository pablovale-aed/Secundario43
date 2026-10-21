# Product

<!-- impeccable:product-schema 1 -->

## Platform

web

## Users

Primary: families and the surrounding community of Barrio Alto Comedero (San Salvador de Jujuy), mostly on phones, finding out about the school's annual student expo. Their job is to decide whether to go, learn when and where it is, and work out how to get there (usually by city bus).

Secondary (not equally weighted): the students who run the stands, who will look for and share their own stand; school staff who publish the page.

## Product Purpose

A single-page event site for **Emprendedores en Acción 2026**, the annual expo of the Colegio Secundario N° 43 "Puerto Argentino". It turns community interest into attendance: it makes the date, the free entry and the route clear, and shows what the students are offering so people want to come.

Success: more families and neighbors show up on the day, knowing the time, place and how to arrive.

## Positioning

This is a real neighborhood school's expo run by its own students, with real stands, real student teams and the school's own identity (the escudo, the "Los Camaleones" emblem and the mascot Cami). It is not a generic event template; the students' work and the school community are the substance.

## Operating Context

- Event: Friday 13 November 2026, 10:00 to 15:00 hs, at the school, Av. Forestal 1185, Barrio Alto Comedero, San Salvador de Jujuy, Argentina.
- Entry is free and open to the whole community.
- Arrival: city bus lines 1, 3, 7, 22 and 48; get off on Av. Forestal at the corner of Teniente López. Google Maps link: https://maps.app.goo.gl/jNkBePiTG3oeEaPM6
- Payment at stands: cash and Mercado Pago transfers by QR at most stands.
- Visitors will mostly use phones, often on mobile data.

## Capabilities and Constraints

- Static `index.html` with Tailwind via CDN, Font Awesome, Google Fonts (Inter) and a Google Maps embed. No build step and no backend.
- All copy is in Spanish (Argentina, voseo: "Descubrí", "Recorré", "Podés").
- Current sections: hero, stands with category filter, countdown, location and buses, digital credential, FAQ, footer.
- The 10 stands are confirmed as real, with their category, description and team name: Comida Saludable (Equipo NutriSalud), Desayunos Saludables (Equipo Mañanas Sanas), Facturas & Panadería (Taller Dulce Sabor), Galletas Artesanales (Equipo Galletitas N°43), Helados Artesanales (Heladería Polar N°43), Licuados & Smoothies (Bar Citrus & Menta), Pizzas & Tacos (Stand Rincón Sabroso), Postres & Delicias (Mesa Dulce Estudiantil), Ramos & Arreglos Florales (Taller Floral N°43), Tacos Tradicionales (Tacos El Camaleón).
- The digital visitor credential with a QR code has no function on the day (nobody scans it) and can be removed if it doesn't add anything. Its QR depends on the external api.qrserver.com service.
- Event motto: "Crea • Innova • Persevera", subtitled "La fórmula del Emprendedor".

## Brand Commitments

- Name: "Emprendedores en Acción 2026"; school: Colegio Secundario N° 43 "Puerto Argentino".
- School identity assets: the escudo (`img/IMG-20261014-WA0001.jpg`), the "Los Camaleones" emblem (`img/IMG-20261013-WA0002.jpg`) and the mascot Cami the chameleon (`img/IMG-20261014-WA0006.jpg`).
- Voice: warm, local and inviting, written in Argentine Spanish.

## Evidence on Hand

- Real photos of the 10 stands in `img/stand/`.
- School escudo, emblem and mascot images in `img/`.
- Confirmed event facts: date, time, address, bus lines, free entry and payment methods.
- Missing: the social media links in the footer point to generic facebook.com, instagram.com and tiktok.com, not to real school accounts. Don't present them as real until real URLs are provided.
- No testimonials, attendance numbers, sponsors or press exist. Don't invent any.

## Product Principles

1. Getting there comes first. Date, time, free entry and the route have to be findable within seconds on a phone.
2. The students' work is the attraction. Real stands, photos and team names carry the page.
3. The school's own identity, not a template's. Use the escudo, Los Camaleones and Cami as given.
4. Only confirmed facts. Unknown details stay out instead of being filled with placeholders.
5. Light on mobile data. The page should load quickly for neighbors on prepaid plans.

## Accessibility & Inclusion

No formal standard specified. The audience covers all ages, including older relatives who will read on phones, so text needs to be legible and the key facts need to be readable without interacting with anything.
