# 🎬 Cinema Ticket Booking System

## 📌 Overview

A backend system for cinema ticket booking with seat selection, session handling, and booking confirmation.

## 🛠️ Tech Stack

* Go (Golang)
* Gorilla Mux
* Redis

## 🚀 How to Run

```bash
git clone https://github.com/<your-username>/cinema-ticket-booking-system.git
cd cinema-ticket-booking-system
go mod tidy
go run main.go
```

## 📡 API Endpoints

### 🎥 Movies

* `GET /movies` → List all movies
* `GET /movies/{movieID}/seats` → View available seats

### 🎟️ Booking

* `POST /movies/{movieID}/seats/{seatID}/hold` → Hold a seat
* `PUT /sessions/{sessionID}/confirm` → Confirm booking
* `DELETE /sessions/{sessionID}` → Release booking

## ✨ Features

* Seat selection system
* Temporary seat holding
* Booking confirmation & release
* Redis-based session management
* Real Time results 

## 📚 Learning

Built to understand backend system design, API handling, and state management using Go.

## Note

This prooject fully idea based from yt