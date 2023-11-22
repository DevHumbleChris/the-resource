# Jetpack Compose Resources

A curated list of resources for Jetpack Compose.

## Official Documentation
- [Jetpack Compose Documentation](https://developer.android.com/jetpack/compose)

## Tutorials
- [Getting Started with Jetpack Compose](https://developer.android.com/codelabs/jetpack-compose-basics)
- [Jetpack Compose Navigation Tutorial](https://developer.android.com/codelabs/jetpack-compose-navigation)

## Sample Projects
- [Jetpack Compose Samples](https://github.com/android/compose-samples)

## Videos
- [Jetpack Compose Basics](https://www.youtube.com/watch?v=Q9MtlmmN4Q0)

## Retrofit dependencies
```
// Retrofit 
implementation("com.squareup.retrofit2:retrofit:2.9.0")
// Retrofit with Scalar Converter
implementation("com.squareup.retrofit2:converter-scalars:2.9.0")

// Update Retrofit with Searilization
implementation("com.jakewharton.retrofit:retrofit2-kotlinx-serialization-converter:1.0.0")
implementation("com.squareup.retrofit2:retrofit:2.9.0")
implementation("com.squareup.okhttp3:okhttp:4.11.0")
implementation("io.coil-kt:coil-compose:2.4.0")
implementation("org.jetbrains.kotlinx:kotlinx-serialization-json:1.5.1")
```

# Android Permissions ( Add Internet Permissions)
1. Open `manifests/AndroidManifest.xml`. Add this line just before the `<application>` tag:

```
<uses-permission android:name="android.permission.INTERNET" />
```

# Coil dependency

```
// Coil
implementation("io.coil-kt:coil-compose:2.4.0")
```
