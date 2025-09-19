### How Palestinians Can Leverage BitChat
#### Written By: The Tech For Palestine Community

<br/>

## What is BitChat?

BitChat is a messaging app that works **without internet**. It uses Bluetooth to connect nearby phones, creating a local network that can't be shut down by authorities.

## Why Gaza Needs BitChat

**In Gaza, internet is often cut off or unreliable. BitChat solves this by:**

- **Working without internet**: Uses Bluetooth to connect nearby phones
- **No phone numbers needed**: Just download and start messaging
- **No servers to block**: Works peer-to-peer between devices
- **Private communication**: Messages stay between you and your contacts

## How to Use BitChat in Gaza

### 1. Download and Setup
- Download BitChat from the app store
- No registration required - just open and start using
- Turn on Bluetooth and location services

### 2. Find Your Network
- BitChat automatically finds other users nearby
- The more people using it, the stronger the network becomes
- Each phone acts as a relay, extending the range

### 3. Start Messaging
- Send text messages to anyone in your Bluetooth range
- Messages hop from phone to phone to reach distant contacts
- Works even when internet is completely down

## Best Practices for Gaza

### Build Your Network
- **Share with family and friends**: The more people using BitChat, the better it works
- **Spread the word**: Tell your community about this tool
- **Keep phones charged**: Each device helps extend the network

### Strategic Use
- **During internet outages**: Use BitChat when regular messaging fails
- **Emergency coordination**: Organize help and share information
- **Local updates**: Share news and safety information with neighbors
- **Family communication**: Stay in touch when other methods don't work

### Device Placement
- **Keep phones close**: Bluetooth works best within 10-30 meters
- **Use as relays**: Position devices to extend network coverage
- **Multiple devices**: The more phones, the stronger the mesh network

## When to Use BitChat

**Use BitChat when:**
- Internet is cut off or very slow
- You need to coordinate with nearby people
- Regular messaging apps aren't working
- You want private communication
- You're in an area with many other BitChat users

**Don't use BitChat when:**
- You need to contact people far away (outside Bluetooth range)
- You need to send large files or photos
- You need guaranteed message delivery
- For life-threatening emergencies (use official channels if available)

## Getting Started Today

1. **Download BitChat** on your phone
2. **Tell your family and friends** to download it too
3. **Test it together** when you're in the same area
4. **Use it during internet outages** to stay connected
5. **Share this guide** with others in your community

## Remember

BitChat is a tool for **local communication** when internet fails. It's not a replacement for regular messaging, but a backup system that works when everything else is down.

**The more people use it, the better it works for everyone.**

---

*This guide is designed specifically for Palestinians in Gaza facing connectivity challenges. BitChat can help maintain communication when traditional methods fail.*

## Technical Concepts That Make BitChat Unique

### Noise Protocol Encryption
BitChat uses the **Noise Protocol Framework** for end-to-end encryption, providing:
- **Forward Secrecy**: Past messages remain secure even if keys are compromised
- **Identity Hiding**: Your identity is encrypted during connection setup
- **Mutual Authentication**: Both parties verify each other's identity
- **Curve25519 Key Exchange**: Modern, secure cryptographic keys
- **ChaCha20-Poly1305 Encryption**: Fast, secure encryption optimized for mobile devices

### Bluetooth Mesh Networks
BitChat creates a **multi-hop mesh network** using Bluetooth Low Energy:
- **Peer-to-Peer Relay**: Messages hop from phone to phone (up to 7 hops)
- **No Central Hub**: Each device acts as both sender and relay
- **Automatic Discovery**: Devices automatically find and connect to nearby users
- **Battery Optimized**: Smart power management to preserve battery life
- **Range Extension**: Network coverage grows with each additional user

### Nostr NIP-17 Protocol (Internet Mode)
When internet is available, BitChat uses **Nostr protocol** with special features:
- **Gift-Wrapped Messages**: Double-encrypted private messages using NIP-17
- **Ephemeral Keys**: Fresh cryptographic identity for each location
- **290+ Global Relays**: Distributed network of servers worldwide
- **Location Channels**: Geographic chat rooms using geohash coordinates
- **No Account Required**: Works without phone numbers or registration

### Geohash Location System
BitChat uses **geohash coordinates** to create location-based channels:
- **Block Level** (7 characters): City block precision
- **Neighborhood** (6 characters): District/area level  
- **City** (5 characters): City-wide communication
- **Province** (4 characters): State/province level
- **Region** (2 characters): Country/regional level

### Dual Transport Architecture
BitChat intelligently chooses the best communication method:
- **Bluetooth First**: Prefers local mesh when available (more private)
- **Internet Fallback**: Uses Nostr relays for global reach
- **Seamless Switching**: Automatically adapts to connectivity changes
- **Hybrid Routing**: Can use both methods simultaneously

### Why These Technologies Matter for Gaza
- **Noise Protocol**: Ensures your messages can't be read even if intercepted
- **Bluetooth Mesh**: Works when internet is completely cut off
- **Nostr Protocol**: Provides global reach when internet is available
- **Geohash System**: Creates local community channels for your area
- **Dual Transport**: Gives you communication options in any situation

