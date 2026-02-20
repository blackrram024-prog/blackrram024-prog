<!--
  BLACKRRAM's PROFILE
  Welcome to the matrix.
  █▀▀ ▄▀█ █▀▄▀█ █▀▀ █▄░█   █▀█ █░█ █▀█ █▀▄▀█ █▀▀ █▄░█
  █▄▄ █▀█ █░▀░█ ██▄ █░▀█   █▀▄ █▄█ █▀▀ █░▀░█ ██▄ █░▀█
-->

# 👨‍💻 RAMEN // BLACKRRAM

```console
root@blackrram:~# whoami
ramen

root@blackrram:~# cat .bashrc | grep EXPERTISE
export EXPERTISE="Cyber Security · Hacking Applications · Mod iOS Apps/Games"
export LANGUAGES="All (literally)"
export STATUS="Professional · Bug Bounty Hunter · iOS Modder"
const blackrram = {
  name: "ramen",
  aka: "blackrram",
  domains: [
    "Cyber Security",
    "Application Hacking",
    "iOS Reverse Engineering",
    "Game Modding",
    "Penetration Testing"
  ],
  languages: [
    "Python", "JavaScript/Node.js", "C/C++", "Java/Kotlin",
    "Swift/Objective-C", "Ruby", "Go", "Rust", "Assembly (x86/ARM)",
    "Bash/PowerShell", "PHP", "HTML/CSS", "SQL", "Lua", "…"
  ],
  tools: [
    "Metasploit", "Burp Suite", "Frida", "GhIdra", "Hopper",
    "Kali Linux", "Wireshark", "Nmap", "MobSF", "CyberChef"
  ],
  currentFocus: "iOS app cracking & security research",
  funFact: "I speak binary and bytecode."
};
# Example: simple port scanner (because why not)
import socket

def scan(target, ports):
    print(f"\n[*] Scanning {target}")
    for port in ports:
        s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)
        s.settimeout(1)
        result = s.connect_ex((target, port))
        if result == 0:
            print(f"[+] Port {port} is open")
        s.close()

if __name__ == "__main__":
    scan("127.0.0.1", [22, 80, 443, 8080])
// iOS kernel exploit snippet (well, not really, but you get the idea)
void tfp0(void) {
    task_t kernel_task;
    kern_return_t err = task_for_pid(mach_task_self(), 0, &kernel_task);
    if (err == KERN_SUCCESS) {
        printf("[+] tfp0 achieved!\n");
    }
}
# Decrypt iOS app binary (jailbroken device)
frida -U -f com.example.app -l dump.js --no-pause

# Resign and install modified .ipa
codesign -f -s "iPhone Developer" Payload/App.app
zip -r modded.ipa Payload/
-- Lua script for game mod (e.g., GTA V mod)
function onPlayerDamage(attacker, damage)
    if attacker == getLocalPlayer() then
        setPlayerHealth(getLocalPlayer(), 100) -- god mode
    end
    return damage
end
addEventHandler("onClientPlayerDamage", root, onPlayerDamage)
Python      ████████████░░░░░░░░  60%
JavaScript  ████████░░░░░░░░░░░░  40%
C/C++       ███████░░░░░░░░░░░░░  35%
Swift/ObjC  ██████░░░░░░░░░░░░░░  30%
Bash        █████░░░░░░░░░░░░░░░  25%
Rust        ████░░░░░░░░░░░░░░░░  20%
Assembly    ██░░░░░░░░░░░░░░░░░░  10%
! Warning: Everything you see here is for educational/research purposes.
! I do not condone illegal activities. Use your powers for good.
