### How Palestinians Can Use BitChat
A Messenger App For Secure Private Chatting With Or Without Internet Access
#### Written By: The Tech For Palestine Community
#### Last Modified: Sep 18, 2025

<br/>

## Abstract

BitChat is a messaging app that works both with or without internet access.

When internet access is cutoff, it uses Bluetooth to connect nearby phones, creating a decentralized local network owned & maintained collectively by all users which means it can't be shut down by authorities. When internet access is available, it uses the Nostr protocol to connect to a global network of relay servers that are owned by both users and organizations and don't rely on a central server.

Traditional messaging apps like Whatsapp & Facebook Messenger depend on centralized infrastructure that can be monitored, censored, or disabled. Bitchat's approach provides censorship resistance, surveillance resistance, and infrastructure independence; The network remains functional during internet outages, natural disasters, protests, or in regions with limited connectivity.

For security & privacy reasons, BitChat doesn't make use of accounts, phone numbers, or central servers. Instead, it uses the noise protocol for end-to-end encryption of all messages and identity verification, whereby a user is identified by random unique public key IDs and their chosen nickname on the app. Finally, BitChat uses a decentralized architecture where the users own the network collectively, as opposed to authoritative messaging platforms like Facebook or WhatsApp owned by Meta.

For technical resources & up-to-date information, see [BitChat's GitHub page](https://github.com/permissionlesstech/bitchat).

## Why Palestinians Should Use BitChat

1. **Uninterrupted Communication**: When internet connectivity is unreliable or completely cut off, BitChat's Bluetooth mesh networking ensures you can still communicate with nearby users. This is crucial in areas where internet access is frequently disrupted.

2. **Privacy and Security**: No phone numbers, no accounts, no central servers means your communications aren't stored on corporate servers or tied to your identity. Your messages stay between you and your intended recipients. Because Bitchat is decentralized, it's not possible for any single entity to censor or surveil the network.

3. **Dual Connectivity**: BitChat seamlessly switches between Bluetooth mesh (for local, offline communication) and internet-based Nostr protocol (for global reach), giving you the best of both worlds.

4. **Geohash Channels**: BitChat shows a list of nearby geographic zone channels based on the user's location, which means that users can find each other easily and communicate with each other without having to know each other's phone numbers or usernames. Examples of such channels include the local mesh (10-50m radius), the local neighborhood (200-1200m radius), Gaza **city**, Palestine, or the entire Middle East.

5. **No Infrastructure Dependencies**: You don't need to set up servers or rely on existing internet infrastructure. BitChat works with just the devices in your network if you don't have internet access & even with internet access, the Nostr protocol is decentralized via relay servers that anyone can setup on their own and doesn't rely on a central server.

## How Can We Get BitChat to Achieve These Benefits

**To maximize BitChat's effectiveness, there are some recommended practices:**

1. **Network Density**: The more people using BitChat in your area, the stronger the mesh network becomes. Encourage community adoption to create robust local communication networks.

2. **Strategic Device Placement**: Position devices strategically to extend the Bluetooth mesh network range. Each device acts as a relay, so proper placement can significantly increase coverage.

3. **Hybrid Connectivity**: Use BitChat's internet connectivity when available for global communication, while relying on Bluetooth mesh for local, reliable messaging during outages.

4. **Community Coordination**: Establish protocols for when to use BitChat vs. other communication methods, ensuring everyone knows how to stay connected during emergencies.

5. **Regular Testing**: Periodically test both connectivity modes to ensure your network is functioning properly and everyone knows how to use the app effectively.

## When to Use BitChat

**Use BitChat when:**

- **Internet connectivity is unreliable or unavailable**: During power outages, internet shutdowns, or in areas with poor connectivity.
- **Privacy is paramount**: When you need to communicate without leaving digital traces on corporate servers.
- **Local coordination is needed**: For community organizing, emergency response, or local event coordination.
- **Censorship resistance is required**: When traditional communication channels are being monitored or blocked.
- **Off-grid communication**: In remote areas or during situations where traditional infrastructure is compromised.
- **Temporary communication needs**: For short-term coordination without the overhead of account creation.

## When Not to Use BitChat

**Avoid using BitChat when:**

- **Long-distance communication is needed**: While BitChat can use internet connectivity, other apps may be more reliable for global communication.
- **Large file sharing is required**: BitChat is optimized for text messaging, not large media files.
- **You need message persistence**: BitChat messages are not stored on servers, so they may not persist across device resets.
- **Integration with existing systems**: If you need to integrate with email, SMS, or other communication systems.
- **Emergency services**: For life-threatening emergencies, use official emergency channels (if available)
- **High-bandwidth applications**: Video calls, large group calls, or streaming content are better served by other applications
- **Privacy is paramount**: From the GitHub page README, "Private messages have not received external security review and may contain vulnerabilities. Do not use for sensitive use cases, and do not rely on its security until it has been reviewed. Now uses the Noise Protocol for identity and encryption. Public local chat (the main feature) has no security concerns."

## Similar Applications

1. **BloomOffline**
   - [GitHub Repository](https://github.com/bloomoffline/Android)
   - Developed in-house by TechForPalestine Community, focusing on off-internet decentralized bluetooth communication for anyone around the world, but especially for Palestinians with limited or poor internet access.

2. **DistributedChat**
   - [GitHub Repository](https://github.com/fwcd/distributed-chat)
   - BloomOffline is based on DistributedChat which is made only for iOS, whereas BloomOffline works on both Android and iOS.
   - A distributed chat messenger that uses Bluetooth LE mesh networks.

3. **Signal**
   - [Official Website](https://signal.org)
   - While excellent for privacy & security, Signal requires internet connectivity and phone numbers.

## Conclusion

BitChat represents a powerful tool for communities facing connectivity challenges. Its dual transport architecture makes it uniquely suited for environments where internet access is unreliable or restricted. By understanding when and how to use BitChat effectively, communities can maintain communication resilience even in the most challenging circumstances.

## References & Citations

- https://github.com/permissionlesstech/bitchat
- ...
- ...
