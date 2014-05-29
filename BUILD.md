# Prerequesites 

 - Maven 3.1

# Download the sources
1. Download robovm 
2. Download libcore64

The to folder must be in the same parent folder 
````
 ;) > dir

29/05/2014  15:15    <REP>          .
29/05/2014  15:15    <REP>          ..
29/05/2014  18:26    <REP>          avian-pack.android.libcore
08/03/2014  23:53    <REP>          robovm
````

# Build robovm-rt.jar

bouncycastle: OpenSSLDigest.java NativeCrypto has move from `org.apache.harmony.xnet.provider.jsse.NativeCrypto` to `import com.android.org.conscrypt.NativeCrypto` 
http://platform--external--bouncycastle.android-source-browsing.googlecode.com/git/bcprov/src/main/java/org/bouncycastle/crypto/digests/OpenSSLDigest.java

# Build