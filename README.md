## Show Test 
##### test lnrdgvoelngrtolqengrtoletolrnetolnrtoeirwlhtgor

## Show Test 
#### ////plugins {
////    id("com.android.application")
////    id("org.jetbrains.kotlin.android")
////}
////
////android {
////    namespace = "kh.com.prasac.mb.feature.home"
////    compileSdk = 33
////
////    defaultConfig {
////        applicationId = "kh.com.prasac.mb.feature.home"
////        minSdk = 24
////        targetSdk = 33
////        versionCode = 1
////        versionName = "1.0"
////
////        testInstrumentationRunner = "androidx.test.runner.AndroidJUnitRunner"
////        vectorDrawables {
////            useSupportLibrary = true
////        }
////    }
////
////    buildTypes {
////        release {
////            isMinifyEnabled = false
////            proguardFiles(
////                getDefaultProguardFile("proguard-android-optimize.txt"),
////                "proguard-rules.pro"
////            )
////        }
////    }
////    compileOptions {
////        sourceCompatibility = JavaVersion.VERSION_1_8
////        targetCompatibility = JavaVersion.VERSION_1_8
////    }
////    kotlinOptions {
////        jvmTarget = "1.8"
////    }
////    buildFeatures {
////        compose = true
////    }
////    composeOptions {
////        kotlinCompilerExtensionVersion = "1.2.0"
////    }
////    packagingOptions {
////        resources {
////            excludes += "/META-INF/{AL2.0,LGPL2.1}"
////        }
////    }
////}
////
////dependencies {
////
////    implementation("androidx.core:core-ktx:1.7.0")
////    implementation("androidx.lifecycle:lifecycle-runtime-ktx:2.3.1")
////    implementation("androidx.activity:activity-compose:1.3.1")
////    implementation("androidx.compose.ui:ui:${rootProject.extra["compose_ui_version"]}")
////    implementation("androidx.compose.ui:ui-tooling-preview:${rootProject.extra["compose_ui_version"]}")
////    implementation("androidx.compose.material:material:1.2.0")
////    testImplementation("junit:junit:4.13.2")
////    androidTestImplementation("androidx.test.ext:junit:1.1.5")
////    androidTestImplementation("androidx.test.espresso:espresso-core:3.5.1")
////    androidTestImplementation("androidx.compose.ui:ui-test-junit4:${rootProject.extra["compose_ui_version"]}")
////    debugImplementation("androidx.compose.ui:ui-tooling:${rootProject.extra["compose_ui_version"]}")
////    debugImplementation("androidx.compose.ui:ui-test-manifest:${rootProject.extra["compose_ui_version"]}")
////}
//@file:Suppress("UnstableApiUsage")
//
//plugins {
//    id("com.android.library")
//    `mb-android-feature`
//}
//
//android {
//    namespace = "kh.com.prasac.mb.feature.home"
//    compileSdk = DepVersions.compileSdk
//    defaultConfig {
//        minSdk = DepVersions.minSdk
//    }
//
//    buildTypes {
//        named("release") {
//            isMinifyEnabled = false
//            proguardFiles(
//                getDefaultProguardFile("proguard-android-optimize.txt"), "proguard-rules.pro"
//            )
//        }
//    }
//
//    compileOptions {
//        sourceCompatibility = DepVersions.javaVersion
//        targetCompatibility = DepVersions.javaVersion
//    }
//
//    kotlinOptions {
//        jvmTarget = DepVersions.kotlinJvmVersion
//    }
//
//    buildFeatures {
//        compose = true
//    }
//
//    composeOptions {
//        kotlinCompilerExtensionVersion = DepVersions.kotlinCompilerExtensionVersion
//    }
//
//    packagingOptions {
//        resources {
//            excludes += "/META-INF/{AL2.0,LGPL2.1}"
//        }
//    }
//}
//
//dependencies {
//   implementation("androidx.navigation:navigation-compose:2.5.3")
//    implementation(projects.domain.info)
//}
