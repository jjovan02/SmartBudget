# SmartBudget 💰

SmartBudget je moderna veb aplikacija za praćenje ličnih finansija, razvijena kao seminarski rad iz predmeta Internet Tehnologije. Aplikacija omogućava korisnicima upravljanje novčanicima, praćenje prihoda i rashoda, postavljanje mesečnih budžeta, transfer novca i vizuelizaciju potrošnje.

## 📄 Dokumentacija

Kompletna projektna dokumentacija dostupna je u [docs/dokumentacija.pdf](docs/dokumentacija.pdf).

## 🚀 Tehnologije

- **Frontend:** Next.js (React), Tailwind CSS, Recharts (za vizuelizaciju)
- **Backend:** Next.js API Routes (REST arhitektura)
- **Baza podataka:** MySQL, Prisma ORM
- **Infrastruktura:** Docker, Docker Compose

## ⚙️ Uputstvo za pokretanje aplikacije (lokalno)

### 1. Preduslovi

- Instaliran [Node.js](https://nodejs.org/) (verzija 18+)
- Instaliran [Docker](https://www.docker.com/products/docker-desktop/) i Docker Desktop
- Instaliran [Git](https://git-scm.com/)

### 2. Kloniranje repozitorijuma

```bash
git clone https://github.com/tvoj-username/internet-tehnologije-2025-smartbudget_2021_0100.git
cd internet-tehnologije-2025-smartbudget_2021_0100
```

### 3. Pokretanje baze podataka

```bash
docker-compose up -d
```

### 4. Instalacija zavisnosti

```bash
npm install
```

### 5. Pokretanje migracija

```bash
npx prisma migrate dev
```

### 6. Pokretanje aplikacije

```bash
npm run dev
```

Aplikacija će biti dostupna na [http://localhost:3000](http://localhost:3000).

## 👥 Autori

- **Jovan Janjušević** — 2021/0172
- **Miloš Purić** — 2021/0100
