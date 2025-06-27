# 🔒 Security Policy

## 🛡️ Supported Versions

We actively support security updates for the following versions of Xonotic:

| Version | Supported          |
| ------- | ------------------ |
| 0.8.5   | ✅ Yes            |
| 0.8.x   | ✅ Yes            |
| 0.7.x   | ❌ No             |
| < 0.7   | ❌ No             |

## 🚨 Reporting a Vulnerability

### 🎮 Game Security Issues

If you discover a security vulnerability in Xonotic, please report it responsibly:

#### 📧 Contact Methods
- **Email**: security@xonotic.org
- **Discord**: Direct message to @Administrators
- **Private**: Do NOT create public issues for security vulnerabilities

#### 📋 Report Format
Please include:
- **Description**: Clear explanation of the vulnerability
- **Impact**: How it affects players/servers
- **Reproduction**: Step-by-step instructions
- **Environment**: Game version, OS, server setup
- **Evidence**: Screenshots, logs, or video proof

### 🚀 Response Timeline

| Stage | Timeline | Action |
|-------|----------|--------|
| **Initial Response** | 24-48 hours | Acknowledge receipt |
| **Investigation** | 1-7 days | Analyze and verify |
| **Fix Development** | 1-14 days | Create and test patch |
| **Release** | 1-3 days | Deploy security update |
| **Disclosure** | After fix | Public security advisory |

## 🔍 Security Scope

### ✅ In Scope
- **Server Exploits**: Remote code execution, crashes
- **Client Vulnerabilities**: Code injection, file access
- **Network Issues**: DDoS amplification, packet manipulation
- **Authentication Bypass**: Server admin circumvention
- **Data Leaks**: Personal information exposure
- **Cheating Infrastructure**: Wallhacks, aimbots at engine level

### ❌ Out of Scope
- **Gameplay Balance**: Weapon strength, map design
- **Standard Cheats**: Typical FPS cheating (use anti-cheat)
- **Social Engineering**: Player impersonation
- **Third-party Mods**: Custom modifications
- **Legacy Versions**: Unsupported game versions
- **Client-side Configs**: Player preference exploits

## ��️ Security Best Practices

### 🎯 Server Administrators
- **Update Regularly**: Always run latest Xonotic version
- **Monitor Logs**: Watch for suspicious activity
- **Limit Permissions**: Restrict admin access
- **Backup Data**: Regular server data backups
- **Network Security**: Use firewalls and DDoS protection

### 🎮 Players
- **Official Downloads**: Only download from xonotic.org
- **Verify Checksums**: Check file integrity
- **Avoid Suspicious Servers**: Don't join untrusted servers
- **Report Cheaters**: Use in-game reporting
- **Update Game**: Keep client updated

## 🏆 Security Hall of Fame

We recognize security researchers who help keep Xonotic safe:

### 🥇 2024 Contributors
- **[Reporter Name]** - Found critical RCE vulnerability
- **[Researcher]** - Discovered authentication bypass
- **[Community Member]** - Reported server crash exploit

*Want to be listed? Report a valid security issue!*

## 📋 Vulnerability Categories

### 🚨 Critical (CVSS 9.0-10.0)
- Remote code execution
- Full system compromise
- Mass server takeover

### ⚠️ High (CVSS 7.0-8.9)  
- Privilege escalation
- Data extraction
- Service disruption

### 📢 Medium (CVSS 4.0-6.9)
- Information disclosure
- Limited DoS attacks
- Authentication issues

### 🔍 Low (CVSS 0.1-3.9)
- Minor information leaks
- Edge case crashes
- Configuration issues

## �� Security Resources

### 📚 Documentation
- [Server Hardening Guide](docs/security/server-hardening.md)
- [Network Security](docs/security/network.md)
- [Anti-Cheat Systems](docs/security/anti-cheat.md)

### 🛡️ Tools
- **Log Analyzer**: Monitor server security
- **Traffic Inspector**: Network packet analysis
- **Integrity Checker**: Verify game files

## 📞 Emergency Contact

For critical security issues requiring immediate attention:

- **Discord**: @SecurityTeam (mention in #emergency)
- **Email**: urgent-security@xonotic.org
- **IRC**: #xonotic-security on QuakeNet

## 🙏 Acknowledgments

Thanks to the gaming security community for keeping Xonotic safe and the competitive FPS scene secure.

---

**Security is everyone's responsibility in competitive gaming!** 🎮🔒
