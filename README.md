# NFT Marketplace

A fully responsive NFT marketplace landing page built with Next.js, featuring dynamic sections for hot collections, new items, top sellers, and category browsing with a modern purple-gradient design system.

Integrated with a live public API to fetch and display real-time NFT data, including collection metadata, item pricing, and seller rankings. No API key or authentication required.

Built as an FES Institute bootcamp project focused on API integration and e-commerce UI patterns.

## Live Demo

[View Live Site](https://nftmarketplace-scott.vercel.app/)

## Features

- Hot Collections - Browse trending NFT collections with live metadata
- New Items - Discover recently listed NFTs with real-time pricing
- Top Sellers - View ranked seller profiles and performance stats
- Category Browsing - Filter and explore NFTs by category
- Responsive Design - Fully optimized for desktop, tablet, and mobile
- Modern UI - Purple-gradient design system with clean, polished aesthetics
- Live API Integration - Real-time NFT data fetched from public cloud functions API
- Skeleton Loading States - Smooth loading experience while data fetches

## Tech Stack

- Next.js - React framework with App Router
- React - UI library
- JavaScript - Core language
- Tailwind CSS - Utility-first styling
- Axios - HTTP client for API requests
- Owl Carousel - Touch-enabled responsive carousel
- REST API - Live NFT data from public cloud functions
- Vercel - Deployment and hosting

## Installation

1. Clone the repository
   ```bash
   git clone https://github.com/ScottS-Frontend/nft-marketplace.git
   cd nft-marketplace
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Run the development server
   ```bash
   npm run dev
   ```

4. Open in browser

   Navigate to http://localhost:3000

## API Reference

This project fetches live NFT data from public cloud functions endpoints:

- Hot Collections: `https://us-central1-nft-cloud-functions.cloudfunctions.net/hotCollections`
- New Items: `https://us-central1-nft-cloud-functions.cloudfunctions.net/newItems`
- Top Sellers: `https://us-central1-nft-cloud-functions.cloudfunctions.net/topSellers`

No API key or authentication is required.

## Screenshots

Add screenshots here to showcase the UI.

## About This Project

This project was built as part of the Frontend Simplified (FES) Institute Bootcamp to demonstrate practical skills in:

- REST API integration and dynamic data rendering
- E-commerce UI patterns and product browsing flows
- Responsive, component-driven layout design
- Modern CSS styling with Tailwind CSS
- Next.js routing and page architecture
- Loading state management and skeleton screens

## License

This project is for educational and portfolio purposes.

Built by Scott Slagle
