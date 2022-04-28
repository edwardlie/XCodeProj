# XCodeProj

React Native Upgrade Helper logo
React Native Upgrade Helper
What's your current react-native version?
0.64.2
To which version would you like to upgrade?
0.68.1
📣 Useful content for upgrading
React Native 0.68 includes preview of the New Architecture opt-in.
See here to learn more about new architecture and how to enable it in your project
React Native 0.68 changelog
Check out Upgrade Support if you are experiencing issues related to React Native during the upgrading process.
Keep in mind that RnDiffApp and rndiffapp are placeholders. When upgrading, you should replace them with your actual project's name. You can also provide your app name by clicking the settings icon on the top right.

Split

Unified
package.json MODIFIED0 hidden comment
{
  "name": "RnDiffApp",
  "name": "rndiffapp",
  "version": "0.0.1",
  "private": true,
  "scripts": {
    "lint": "eslint ."
  },
  "dependencies": {
    "react": "17.0.1",
    "react-native": "0.64.2"
    "react": "17.0.2",
    "react-native": "0.68.1"
  },
  "devDependencies": {
    "@babel/core": "^7.12.9",
    "@babel/runtime": "^7.12.5",
    "@react-native-community/eslint-config": "^2.0.0",
    "babel-jest": "^26.6.3",
    "eslint": "7.14.0",
    "eslint": "^7.32.0",
    "jest": "^26.6.3",
    "metro-react-native-babel-preset": "^0.64.0",
    "react-test-renderer": "17.0.1"
    "metro-react-native-babel-preset": "^0.67.0",
    "react-test-renderer": "17.0.2"
  },
  "jest": {
    "preset": "react-native"
.bundle/config ADDED0 hidden comment
BUNDLE_PATH: "vendor/bundle"
BUNDLE_FORCE_RUBY_PLATFORM: 1
.flowconfig MODIFIED0 hidden comment
; Flow doesn't support platforms
.*/Libraries/Utilities/LoadingView.js
.*/node_modules/resolve/test/resolver/malformed_package_json/package\.json$
[untyped]
.*/node_modules/@react-native-community/cli/.*/.*
[options]
emoji=true
esproposal.optional_chaining=enable
esproposal.nullish_coalescing=enable
exact_by_default=true
format.bracket_spacing=false
module.file_ext=.js
module.file_ext=.json
module.file_ext=.ios.js
untyped-type-import
[version]
^0.137.0
^0.170.0
.gitattributes DELETED0 hidden comment
.gitignore MODIFIED0 hidden comment
.gradle
local.properties
*.iml
*.hprof
# node.js
#
# Bundle artifact
*.jsbundle
# CocoaPods
# Ruby / CocoaPods
/ios/Pods/
/vendor/bundle/
.prettierrc.js MODIFIED0 hidden comment
module.exports = {
  arrowParens: 'avoid',
  bracketSameLine: true,
  bracketSpacing: false,
  jsxBracketSameLine: true,
  singleQuote: true,
  trailingComma: 'all',
  arrowParens: 'avoid',
};
.ruby-version ADDED0 hidden comment
2.7.4
Gemfile ADDED0 hidden comment
source 'https://rubygems.org'
# You may use http://rbenv.org/ or https://rvm.io/ to install and use this version
ruby '2.7.4'
gem 'cocoapods', '~> 1.11', '>= 1.11.2'
Gemfile.lock ADDED0 hidden comment
GEM
  remote: https://rubygems.org/
  specs:
    CFPropertyList (3.0.5)
      rexml
    activesupport (6.1.5)
      concurrent-ruby (~> 1.0, >= 1.0.2)
      i18n (>= 1.6, < 2)
      minitest (>= 5.1)
      tzinfo (~> 2.0)
      zeitwerk (~> 2.3)
    addressable (2.8.0)
      public_suffix (>= 2.0.2, < 5.0)
    algoliasearch (1.27.5)
      httpclient (~> 2.8, >= 2.8.3)
      json (>= 1.5.1)
    atomos (0.1.3)
    claide (1.1.0)
    cocoapods (1.11.3)
      addressable (~> 2.8)
      claide (>= 1.0.2, < 2.0)
      cocoapods-core (= 1.11.3)
      cocoapods-deintegrate (>= 1.0.3, < 2.0)
      cocoapods-downloader (>= 1.4.0, < 2.0)
      cocoapods-plugins (>= 1.0.0, < 2.0)
      cocoapods-search (>= 1.0.0, < 2.0)
      cocoapods-trunk (>= 1.4.0, < 2.0)
      cocoapods-try (>= 1.1.0, < 2.0)
      colored2 (~> 3.1)
      escape (~> 0.0.4)
      fourflusher (>= 2.3.0, < 3.0)
      gh_inspector (~> 1.0)
      molinillo (~> 0.8.0)
      nap (~> 1.0)
      ruby-macho (>= 1.0, < 3.0)
      xcodeproj (>= 1.21.0, < 2.0)
    cocoapods-core (1.11.3)
      activesupport (>= 5.0, < 7)
      addressable (~> 2.8)
      algoliasearch (~> 1.0)
      concurrent-ruby (~> 1.1)
      fuzzy_match (~> 2.0.4)
      nap (~> 1.0)
      netrc (~> 0.11)
      public_suffix (~> 4.0)
      typhoeus (~> 1.0)
    cocoapods-deintegrate (1.0.5)
    cocoapods-downloader (1.6.3)
    cocoapods-plugins (1.0.0)
      nap
    cocoapods-search (1.0.1)
    cocoapods-trunk (1.6.0)
      nap (>= 0.8, < 2.0)
      netrc (~> 0.11)
    cocoapods-try (1.2.0)
    colored2 (3.1.2)
    concurrent-ruby (1.1.10)
    escape (0.0.4)
    ethon (0.15.0)
      ffi (>= 1.15.0)
    ffi (1.15.5)
    fourflusher (2.3.1)
    fuzzy_match (2.0.4)
    gh_inspector (1.1.3)
    httpclient (2.8.3)
    i18n (1.10.0)
      concurrent-ruby (~> 1.0)
    json (2.6.1)
    minitest (5.15.0)
    molinillo (0.8.0)
    nanaimo (0.3.0)
    nap (1.1.0)
    netrc (0.11.0)
    public_suffix (4.0.7)
    rexml (3.2.5)
    ruby-macho (2.5.1)
    typhoeus (1.4.0)
      ethon (>= 0.9.0)
    tzinfo (2.0.4)
      concurrent-ruby (~> 1.0)
    xcodeproj (1.21.0)
      CFPropertyList (>= 2.3.3, < 4.0)
      atomos (~> 0.1.3)
      claide (>= 1.0.2, < 2.0)
      colored2 (~> 3.1)
      nanaimo (~> 0.3.0)
      rexml (~> 3.2.4)
    zeitwerk (2.5.4)
PLATFORMS
  ruby
DEPENDENCIES
  cocoapods (~> 1.11, >= 1.11.2)
RUBY VERSION
   ruby 2.7.4p191
BUNDLED WITH
   2.2.27
_editorconfig DELETED0 hidden comment
android/app/build.gradle MODIFIED2 hidden comments
apply plugin: "com.android.application"
import com.android.build.OutputFile
import org.apache.tools.ant.taskdefs.condition.Os
/**
 * The react.gradle file registers a task for each build variant (e.g. bundleDebugJsAndAssets
/**
 * Whether to enable the Hermes VM.
 *
 * This should be set on project.ext.react and mirrored here.  If it is not set
 * This should be set on project.ext.react and that value will be read here. If it is not set
 * on project.ext.react, JavaScript will not be compiled to Hermes Bytecode
 * and the benefits of using Hermes will therefore be sharply reduced.
 */
def enableHermes = project.ext.react.get("enableHermes", false);
/**
 * Architectures to build native code for.
 */
def reactNativeArchitectures() {
    def value = project.getProperties().get("reactNativeArchitectures")
    return value ? value.split(",") : ["armeabi-v7a", "x86", "x86_64", "arm64-v8a"]
}
android {
    ndkVersion rootProject.ext.ndkVersion
    compileSdkVersion rootProject.ext.compileSdkVersion
    compileOptions {
        sourceCompatibility JavaVersion.VERSION_1_8
        targetCompatibility JavaVersion.VERSION_1_8
    }
    defaultConfig {
        applicationId "com.rndiffapp"
        minSdkVersion rootProject.ext.minSdkVersion
        targetSdkVersion rootProject.ext.targetSdkVersion
        versionCode 1
        versionName "1.0"
        buildConfigField "boolean", "IS_NEW_ARCHITECTURE_ENABLED", isNewArchitectureEnabled().toString()
        if (isNewArchitectureEnabled()) {
            // We configure the NDK build only if you decide to opt-in for the New Architecture.
            externalNativeBuild {
                ndkBuild {
                    arguments "APP_PLATFORM=android-21",
                        "APP_STL=c++_shared",
                        "NDK_TOOLCHAIN_VERSION=clang",
                        "GENERATED_SRC_DIR=$buildDir/generated/source",
                        "PROJECT_BUILD_DIR=$buildDir",
                        "REACT_ANDROID_DIR=$rootDir/../node_modules/react-native/ReactAndroid",
                        "REACT_ANDROID_BUILD_DIR=$rootDir/../node_modules/react-native/ReactAndroid/build"
                    cFlags "-Wall", "-Werror", "-fexceptions", "-frtti", "-DWITH_INSPECTOR=1"
                    cppFlags "-std=c++17"
                    // Make sure this target name is the same you specify inside the
                    // src/main/jni/Android.mk file for the `LOCAL_MODULE` variable.
                    targets "rndiffapp_appmodules"
                    // Fix for windows limit on number of character in file paths and in command lines
                    if (Os.isFamily(Os.FAMILY_WINDOWS)) {
                        arguments "NDK_OUT=${rootProject.projectDir.getParent()}\\.cxx",
                            "NDK_APP_SHORT_COMMANDS=true"
                    }
                }
            }
            if (!enableSeparateBuildPerCPUArchitecture) {
                ndk {
                    abiFilters (*reactNativeArchitectures())
                }
            }
        }
    }
    if (isNewArchitectureEnabled()) {
        // We configure the NDK build only if you decide to opt-in for the New Architecture.
        externalNativeBuild {
            ndkBuild {
                path "$projectDir/src/main/jni/Android.mk"
            }
        }
        def reactAndroidProjectDir = project(':ReactAndroid').projectDir
        def packageReactNdkDebugLibs = tasks.register("packageReactNdkDebugLibs", Copy) {
            dependsOn(":ReactAndroid:packageReactNdkDebugLibsForBuck")
            from("$reactAndroidProjectDir/src/main/jni/prebuilt/lib")
            into("$buildDir/react-ndk/exported")
        }
        def packageReactNdkReleaseLibs = tasks.register("packageReactNdkReleaseLibs", Copy) {
            dependsOn(":ReactAndroid:packageReactNdkReleaseLibsForBuck")
            from("$reactAndroidProjectDir/src/main/jni/prebuilt/lib")
            into("$buildDir/react-ndk/exported")
        }
        afterEvaluate {
            // If you wish to add a custom TurboModule or component locally,
            // you should uncomment this line.
            // preBuild.dependsOn("generateCodegenArtifactsFromSchema")
            preDebugBuild.dependsOn(packageReactNdkDebugLibs)
            preReleaseBuild.dependsOn(packageReactNdkReleaseLibs)
            // Due to a bug inside AGP, we have to explicitly set a dependency
            // between configureNdkBuild* tasks and the preBuild tasks.
            // This can be removed once this is solved: https://issuetracker.google.com/issues/207403732
            configureNdkBuildRelease.dependsOn(preReleaseBuild)
            configureNdkBuildDebug.dependsOn(preDebugBuild)
            reactNativeArchitectures().each { architecture ->
                tasks.findByName("configureNdkBuildDebug[${architecture}]")?.configure {
                    dependsOn("preDebugBuild")
                }
                tasks.findByName("configureNdkBuildRelease[${architecture}]")?.configure {
                    dependsOn("preReleaseBuild")
                }
            }
        }
    }
    splits {
        abi {
            reset()
            enable enableSeparateBuildPerCPUArchitecture
            universalApk false  // If true, also generate a universal APK
            include "armeabi-v7a", "x86", "arm64-v8a", "x86_64"
            include (*reactNativeArchitectures())
        }
    }
    signingConfigs {
dependencies {
    implementation fileTree(dir: "libs", include: ["*.jar"])
    //noinspection GradleDynamicVersion
    implementation "com.facebook.react:react-native:+"  // From node_modules
    implementation "androidx.swiperefreshlayout:swiperefreshlayout:1.0.0"
    debugImplementation("com.facebook.flipper:flipper:${FLIPPER_VERSION}") {
      exclude group:'com.facebook.fbjni'
        exclude group:'com.facebook.fbjni'
    }
    debugImplementation("com.facebook.flipper:flipper-network-plugin:${FLIPPER_VERSION}") {
    }
}
if (isNewArchitectureEnabled()) {
    // If new architecture is enabled, we let you build RN from source
    // Otherwise we fallback to a prebuilt .aar bundled in the NPM package.
    // This will be applied to all the imported transtitive dependency.
    configurations.all {
        resolutionStrategy.dependencySubstitution {
            substitute(module("com.facebook.react:react-native"))
                    .using(project(":ReactAndroid")).because("On New Architecture we're building React Native from source")
        }
    }
}
// Run this once to be able to run the application with BUCK
// puts all compile dependencies into folder libs for BUCK to use
task copyDownloadableDepsToLibs(type: Copy) {
    from configurations.compile
    from configurations.implementation
    into 'libs'
}
apply from: file("../../node_modules/@react-native-community/cli-platform-android/native_modules.gradle"); applyNativeModulesAppBuildGradle(project)
def isNewArchitectureEnabled() {
    // To opt-in for the New Architecture, you can either:
    // - Set `newArchEnabled` to true inside the `gradle.properties` file
    // - Invoke gradle with `-newArchEnabled=true`
    // - Set an environment variable `ORG_GRADLE_PROJECT_newArchEnabled=true`
    return project.hasProperty("newArchEnabled") && project.newArchEnabled == "true"
}
android/app/src/debug/AndroidManifest.xml MODIFIED0 hidden comment
        android:usesCleartextTraffic="true"
        tools:targetApi="28"
        tools:ignore="GoogleAppIndexingWarning">
        <activity android:name="com.facebook.react.devsupport.DevSettingsActivity" />
        <activity android:name="com.facebook.react.devsupport.DevSettingsActivity" android:exported="false" />
    </application>
</manifest>
android/app/src/debug/java/com/rndiffapp/ReactNativeFlipper.java MODIFIED0 hidden comment
/**
 * Copyright (c) Facebook, Inc. and its affiliates.
 * Copyright (c) Meta Platforms, Inc. and affiliates.
 *
 * <p>This source code is licensed under the MIT license found in the LICENSE file in the root
 * directory of this source tree.
import com.facebook.flipper.plugins.network.NetworkFlipperPlugin;
import com.facebook.flipper.plugins.react.ReactFlipperPlugin;
import com.facebook.flipper.plugins.sharedpreferences.SharedPreferencesFlipperPlugin;
import com.facebook.react.ReactInstanceEventListener;
import com.facebook.react.ReactInstanceManager;
import com.facebook.react.bridge.ReactContext;
import com.facebook.react.modules.network.NetworkingModule;
      ReactContext reactContext = reactInstanceManager.getCurrentReactContext();
      if (reactContext == null) {
        reactInstanceManager.addReactInstanceEventListener(
            new ReactInstanceManager.ReactInstanceEventListener() {
            new ReactInstanceEventListener() {
              @Override
              public void onReactContextInitialized(ReactContext reactContext) {
                reactInstanceManager.removeReactInstanceEventListener(this);
android/app/src/main/AndroidManifest.xml MODIFIED0 hidden comment
      <activity
        android:name=".MainActivity"
        android:label="@string/app_name"
        android:configChanges="keyboard|keyboardHidden|orientation|screenSize|uiMode"
        android:configChanges="keyboard|keyboardHidden|orientation|screenLayout|screenSize|smallestScreenSize|uiMode"
        android:launchMode="singleTask"
        android:windowSoftInputMode="adjustResize">
        android:windowSoftInputMode="adjustResize"
        android:exported="true">
        <intent-filter>
            <action android:name="android.intent.action.MAIN" />
            <category android:name="android.intent.category.LAUNCHER" />
android/app/src/main/java/com/rndiffapp/MainActivity.java MODIFIED1 hidden comment
package com.rndiffapp;
import com.facebook.react.ReactActivity;
import com.facebook.react.ReactActivityDelegate;
import com.facebook.react.ReactRootView;
public class MainActivity extends ReactActivity {
  protected String getMainComponentName() {
    return "RnDiffApp";
  }
  /**
   * Returns the instance of the {@link ReactActivityDelegate}. There the RootView is created and
   * you can specify the rendered you wish to use (Fabric or the older renderer).
   */
  @Override
  protected ReactActivityDelegate createReactActivityDelegate() {
    return new MainActivityDelegate(this, getMainComponentName());
  }
  public static class MainActivityDelegate extends ReactActivityDelegate {
    public MainActivityDelegate(ReactActivity activity, String mainComponentName) {
      super(activity, mainComponentName);
    }
    @Override
    protected ReactRootView createRootView() {
      ReactRootView reactRootView = new ReactRootView(getContext());
      // If you opted-in for the New Architecture, we enable the Fabric Renderer.
      reactRootView.setIsFabric(BuildConfig.IS_NEW_ARCHITECTURE_ENABLED);
      return reactRootView;
    }
  }
}
android/app/src/main/java/com/rndiffapp/MainApplication.java MODIFIED0 hidden comment
import com.facebook.react.ReactInstanceManager;
import com.facebook.react.ReactNativeHost;
import com.facebook.react.ReactPackage;
import com.facebook.react.config.ReactFeatureFlags;
import com.facebook.soloader.SoLoader;
import com.rndiffapp.newarchitecture.MainApplicationReactNativeHost;
import java.lang.reflect.InvocationTargetException;
import java.util.List;
        }
      };
  private final ReactNativeHost mNewArchitectureNativeHost =
      new MainApplicationReactNativeHost(this);
  @Override
  public ReactNativeHost getReactNativeHost() {
    return mReactNativeHost;
    if (BuildConfig.IS_NEW_ARCHITECTURE_ENABLED) {
      return mNewArchitectureNativeHost;
    } else {
      return mReactNativeHost;
    }
  }
  @Override
  public void onCreate() {
    super.onCreate();
    // If you opted-in for the New Architecture, we enable the TurboModule system
    ReactFeatureFlags.useTurboModules = BuildConfig.IS_NEW_ARCHITECTURE_ENABLED;
    SoLoader.init(this, /* native exopackage */ false);
    initializeFlipper(this, getReactNativeHost().getReactInstanceManager());
  }
android/app/src/main/java/com/rndiffapp/newarchitecture/MainApplicationReactNativeHost.java ADDED1 hidden comment
package com.rndiffapp.newarchitecture;
import android.app.Application;
import androidx.annotation.NonNull;
import com.facebook.react.PackageList;
import com.facebook.react.ReactInstanceManager;
import com.facebook.react.ReactNativeHost;
import com.facebook.react.ReactPackage;
import com.facebook.react.ReactPackageTurboModuleManagerDelegate;
import com.facebook.react.bridge.JSIModulePackage;
import com.facebook.react.bridge.JSIModuleProvider;
import com.facebook.react.bridge.JSIModuleSpec;
import com.facebook.react.bridge.JSIModuleType;
import com.facebook.react.bridge.JavaScriptContextHolder;
import com.facebook.react.bridge.ReactApplicationContext;
import com.facebook.react.bridge.UIManager;
import com.facebook.react.fabric.ComponentFactory;
import com.facebook.react.fabric.CoreComponentsRegistry;
import com.facebook.react.fabric.EmptyReactNativeConfig;
import com.facebook.react.fabric.FabricJSIModuleProvider;
import com.facebook.react.uimanager.ViewManagerRegistry;
import com.rndiffapp.BuildConfig;
import com.rndiffapp.newarchitecture.components.MainComponentsRegistry;
import com.rndiffapp.newarchitecture.modules.MainApplicationTurboModuleManagerDelegate;
import java.util.ArrayList;
import java.util.List;
/**
 * A {@link ReactNativeHost} that helps you load everything needed for the New Architecture, both
 * TurboModule delegates and the Fabric Renderer.
 *
 * <p>Please note that this class is used ONLY if you opt-in for the New Architecture (see the
 * `newArchEnabled` property). Is ignored otherwise.
 */
public class MainApplicationReactNativeHost extends ReactNativeHost {
  public MainApplicationReactNativeHost(Application application) {
    super(application);
  }
  @Override
  public boolean getUseDeveloperSupport() {
    return BuildConfig.DEBUG;
  }
  @Override
  protected List<ReactPackage> getPackages() {
    List<ReactPackage> packages = new PackageList(this).getPackages();
    // Packages that cannot be autolinked yet can be added manually here, for example:
    //     packages.add(new MyReactNativePackage());
    // TurboModules must also be loaded here providing a valid TurboReactPackage implementation:
    //     packages.add(new TurboReactPackage() { ... });
    // If you have custom Fabric Components, their ViewManagers should also be loaded here
    // inside a ReactPackage.
    return packages;
  }
  @Override
  protected String getJSMainModuleName() {
    return "index";
  }
  @NonNull
  @Override
  protected ReactPackageTurboModuleManagerDelegate.Builder
      getReactPackageTurboModuleManagerDelegateBuilder() {
    // Here we provide the ReactPackageTurboModuleManagerDelegate Builder. This is necessary
    // for the new architecture and to use TurboModules correctly.
    return new MainApplicationTurboModuleManagerDelegate.Builder();
  }
  @Override
  protected JSIModulePackage getJSIModulePackage() {
    return new JSIModulePackage() {
      @Override
      public List<JSIModuleSpec> getJSIModules(
          final ReactApplicationContext reactApplicationContext,
          final JavaScriptContextHolder jsContext) {
        final List<JSIModuleSpec> specs = new ArrayList<>();
        // Here we provide a new JSIModuleSpec that will be responsible of providing the
        // custom Fabric Components.
        specs.add(
            new JSIModuleSpec() {
              @Override
              public JSIModuleType getJSIModuleType() {
                return JSIModuleType.UIManager;
              }
              @Override
              public JSIModuleProvider<UIManager> getJSIModuleProvider() {
                final ComponentFactory componentFactory = new ComponentFactory();
                CoreComponentsRegistry.register(componentFactory);
                // Here we register a Components Registry.
                // The one that is generated with the template contains no components
                // and just provides you the one from React Native core.
                MainComponentsRegistry.register(componentFactory);
                final ReactInstanceManager reactInstanceManager = getReactInstanceManager();
                ViewManagerRegistry viewManagerRegistry =
                    new ViewManagerRegistry(
                        reactInstanceManager.getOrCreateViewManagers(reactApplicationContext));
                return new FabricJSIModuleProvider(
                    reactApplicationContext,
                    componentFactory,
                    new EmptyReactNativeConfig(),
                    viewManagerRegistry);
              }
            });
        return specs;
      }
    };
  }
}
android/app/src/main/java/com/rndiffapp/newarchitecture/components/MainComponentsRegistry.java ADDED1 hidden comment
package com.rndiffapp.newarchitecture.components;
import com.facebook.jni.HybridData;
import com.facebook.proguard.annotations.DoNotStrip;
import com.facebook.react.fabric.ComponentFactory;
import com.facebook.soloader.SoLoader;
/**
 * Class responsible to load the custom Fabric Components. This class has native methods and needs a
 * corresponding C++ implementation/header file to work correctly (already placed inside the jni/
 * folder for you).
 *
 * <p>Please note that this class is used ONLY if you opt-in for the New Architecture (see the
 * `newArchEnabled` property). Is ignored otherwise.
 */
@DoNotStrip
public class MainComponentsRegistry {
  static {
    SoLoader.loadLibrary("fabricjni");
  }
  @DoNotStrip private final HybridData mHybridData;
  @DoNotStrip
  private native HybridData initHybrid(ComponentFactory componentFactory);
  @DoNotStrip
  private MainComponentsRegistry(ComponentFactory componentFactory) {
    mHybridData = initHybrid(componentFactory);
  }
  @DoNotStrip
  public static MainComponentsRegistry register(ComponentFactory componentFactory) {
    return new MainComponentsRegistry(componentFactory);
  }
}
android/app/src/main/java/com/rndiffapp/newarchitecture/modules/MainApplicationTurboModuleManagerDelegate.java ADDED1 hidden comment
package com.rndiffapp.newarchitecture.modules;
import com.facebook.jni.HybridData;
import com.facebook.react.ReactPackage;
import com.facebook.react.ReactPackageTurboModuleManagerDelegate;
import com.facebook.react.bridge.ReactApplicationContext;
import com.facebook.soloader.SoLoader;
import java.util.List;
/**
 * Class responsible to load the TurboModules. This class has native methods and needs a
 * corresponding C++ implementation/header file to work correctly (already placed inside the jni/
 * folder for you).
 *
 * <p>Please note that this class is used ONLY if you opt-in for the New Architecture (see the
 * `newArchEnabled` property). Is ignored otherwise.
 */
public class MainApplicationTurboModuleManagerDelegate
    extends ReactPackageTurboModuleManagerDelegate {
  private static volatile boolean sIsSoLibraryLoaded;
  protected MainApplicationTurboModuleManagerDelegate(
      ReactApplicationContext reactApplicationContext, List<ReactPackage> packages) {
    super(reactApplicationContext, packages);
  }
  protected native HybridData initHybrid();
  native boolean canCreateTurboModule(String moduleName);
  public static class Builder extends ReactPackageTurboModuleManagerDelegate.Builder {
    protected MainApplicationTurboModuleManagerDelegate build(
        ReactApplicationContext context, List<ReactPackage> packages) {
      return new MainApplicationTurboModuleManagerDelegate(context, packages);
    }
  }
  @Override
  protected synchronized void maybeLoadOtherSoLibraries() {
    if (!sIsSoLibraryLoaded) {
      // If you change the name of your application .so file in the Android.mk file,
      // make sure you update the name here as well.
      SoLoader.loadLibrary("rndiffapp_appmodules");
      sIsSoLibraryLoaded = true;
    }
  }
}
android/app/src/main/jni/Android.mk ADDED1 hidden comment
THIS_DIR := $(call my-dir)
include $(REACT_ANDROID_DIR)/Android-prebuilt.mk
# If you wish to add a custom TurboModule or Fabric component in your app you
# will have to include the following autogenerated makefile.
# include $(GENERATED_SRC_DIR)/codegen/jni/Android.mk
include $(CLEAR_VARS)
LOCAL_PATH := $(THIS_DIR)
# You can customize the name of your application .so file here.
LOCAL_MODULE := rndiffapp_appmodules
LOCAL_C_INCLUDES := $(LOCAL_PATH)
LOCAL_SRC_FILES := $(wildcard $(LOCAL_PATH)/*.cpp)
LOCAL_EXPORT_C_INCLUDES := $(LOCAL_PATH)
# If you wish to add a custom TurboModule or Fabric component in your app you
# will have to uncomment those lines to include the generated source 
# files from the codegen (placed in $(GENERATED_SRC_DIR)/codegen/jni)
#
# LOCAL_C_INCLUDES += $(GENERATED_SRC_DIR)/codegen/jni
# LOCAL_SRC_FILES += $(wildcard $(GENERATED_SRC_DIR)/codegen/jni/*.cpp)
# LOCAL_EXPORT_C_INCLUDES += $(GENERATED_SRC_DIR)/codegen/jni
# Here you should add any native library you wish to depend on.
LOCAL_SHARED_LIBRARIES := \
  libfabricjni \
  libfbjni \
  libfolly_futures \
  libfolly_json \
  libglog \
  libjsi \
  libreact_codegen_rncore \
  libreact_debug \
  libreact_nativemodule_core \
  libreact_render_componentregistry \
  libreact_render_core \
  libreact_render_debug \
  libreact_render_graphics \
  librrc_view \
  libruntimeexecutor \
  libturbomodulejsijni \
  libyoga
LOCAL_CFLAGS := -DLOG_TAG=\"ReactNative\" -fexceptions -frtti -std=c++17 -Wall
include $(BUILD_SHARED_LIBRARY)
android/app/src/main/jni/MainApplicationModuleProvider.cpp ADDED1 hidden comment
#include "MainApplicationModuleProvider.h"
#include <rncore.h>
namespace facebook {
namespace react {
std::shared_ptr<TurboModule> MainApplicationModuleProvider(
    const std::string moduleName,
    const JavaTurboModule::InitParams &params) {
  // Here you can provide your own module provider for TurboModules coming from
  // either your application or from external libraries. The approach to follow
  // is similar to the following (for a library called `samplelibrary`:
  //
  // auto module = samplelibrary_ModuleProvider(moduleName, params);
  // if (module != nullptr) {
  //    return module;
  // }
  // return rncore_ModuleProvider(moduleName, params);
  return rncore_ModuleProvider(moduleName, params);
}
} // namespace react
} // namespace facebook
android/app/src/main/jni/MainApplicationModuleProvider.h ADDED1 hidden comment
#pragma once
#include <memory>
#include <string>
#include <ReactCommon/JavaTurboModule.h>
namespace facebook {
namespace react {
std::shared_ptr<TurboModule> MainApplicationModuleProvider(
    const std::string moduleName,
    const JavaTurboModule::InitParams &params);
} // namespace react
} // namespace facebook
android/app/src/main/jni/MainApplicationTurboModuleManagerDelegate.cpp ADDED1 hidden comment
#include "MainApplicationTurboModuleManagerDelegate.h"
#include "MainApplicationModuleProvider.h"
namespace facebook {
namespace react {
jni::local_ref<MainApplicationTurboModuleManagerDelegate::jhybriddata>
MainApplicationTurboModuleManagerDelegate::initHybrid(
    jni::alias_ref<jhybridobject>) {
  return makeCxxInstance();
}
void MainApplicationTurboModuleManagerDelegate::registerNatives() {
  registerHybrid({
      makeNativeMethod(
          "initHybrid", MainApplicationTurboModuleManagerDelegate::initHybrid),
      makeNativeMethod(
          "canCreateTurboModule",
          MainApplicationTurboModuleManagerDelegate::canCreateTurboModule),
  });
}
std::shared_ptr<TurboModule>
MainApplicationTurboModuleManagerDelegate::getTurboModule(
    const std::string name,
    const std::shared_ptr<CallInvoker> jsInvoker) {
  // Not implemented yet: provide pure-C++ NativeModules here.
  return nullptr;
}
std::shared_ptr<TurboModule>
MainApplicationTurboModuleManagerDelegate::getTurboModule(
    const std::string name,
    const JavaTurboModule::InitParams &params) {
  return MainApplicationModuleProvider(name, params);
}
bool MainApplicationTurboModuleManagerDelegate::canCreateTurboModule(
    std::string name) {
  return getTurboModule(name, nullptr) != nullptr ||
      getTurboModule(name, {.moduleName = name}) != nullptr;
}
} // namespace react
} // namespace facebook
android/app/src/main/jni/MainApplicationTurboModuleManagerDelegate.h ADDED1 hidden comment
#include <memory>
#include <string>
#include <ReactCommon/TurboModuleManagerDelegate.h>
#include <fbjni/fbjni.h>
namespace facebook {
namespace react {
class MainApplicationTurboModuleManagerDelegate
    : public jni::HybridClass<
          MainApplicationTurboModuleManagerDelegate,
          TurboModuleManagerDelegate> {
 public:
  // Adapt it to the package you used for your Java class.
  static constexpr auto kJavaDescriptor =
      "Lcom/rndiffapp/newarchitecture/modules/MainApplicationTurboModuleManagerDelegate;";
  static jni::local_ref<jhybriddata> initHybrid(jni::alias_ref<jhybridobject>);
  static void registerNatives();
  std::shared_ptr<TurboModule> getTurboModule(
      const std::string name,
      const std::shared_ptr<CallInvoker> jsInvoker) override;
  std::shared_ptr<TurboModule> getTurboModule(
      const std::string name,
      const JavaTurboModule::InitParams &params) override;
  /**
   * Test-only method. Allows user to verify whether a TurboModule can be
   * created by instances of this class.
   */
  bool canCreateTurboModule(std::string name);
};
} // namespace react
} // namespace facebook
android/app/src/main/jni/MainComponentsRegistry.cpp ADDED1 hidden comment
#include "MainComponentsRegistry.h"
#include <CoreComponentsRegistry.h>
#include <fbjni/fbjni.h>
#include <react/renderer/componentregistry/ComponentDescriptorProviderRegistry.h>
#include <react/renderer/components/rncore/ComponentDescriptors.h>
namespace facebook {
namespace react {
MainComponentsRegistry::MainComponentsRegistry(ComponentFactory *delegate) {}
std::shared_ptr<ComponentDescriptorProviderRegistry const>
MainComponentsRegistry::sharedProviderRegistry() {
  auto providerRegistry = CoreComponentsRegistry::sharedProviderRegistry();
  // Custom Fabric Components go here. You can register custom
  // components coming from your App or from 3rd party libraries here.
  //
  // providerRegistry->add(concreteComponentDescriptorProvider<
  //        AocViewerComponentDescriptor>());
  return providerRegistry;
}
jni::local_ref<MainComponentsRegistry::jhybriddata>
MainComponentsRegistry::initHybrid(
    jni::alias_ref<jclass>,
    ComponentFactory *delegate) {
  auto instance = makeCxxInstance(delegate);
  auto buildRegistryFunction =
      [](EventDispatcher::Weak const &eventDispatcher,
         ContextContainer::Shared const &contextContainer)
      -> ComponentDescriptorRegistry::Shared {
    auto registry = MainComponentsRegistry::sharedProviderRegistry()
                        ->createComponentDescriptorRegistry(
                            {eventDispatcher, contextContainer});
    auto mutableRegistry =
        std::const_pointer_cast<ComponentDescriptorRegistry>(registry);
    mutableRegistry->setFallbackComponentDescriptor(
        std::make_shared<UnimplementedNativeViewComponentDescriptor>(
            ComponentDescriptorParameters{
                eventDispatcher, contextContainer, nullptr}));
    return registry;
  };
  delegate->buildRegistryFunction = buildRegistryFunction;
  return instance;
}
void MainComponentsRegistry::registerNatives() {
  registerHybrid({
      makeNativeMethod("initHybrid", MainComponentsRegistry::initHybrid),
  });
}
} // namespace react
} // namespace facebook
android/app/src/main/jni/MainComponentsRegistry.h ADDED1 hidden comment
#pragma once
#include <ComponentFactory.h>
#include <fbjni/fbjni.h>
#include <react/renderer/componentregistry/ComponentDescriptorProviderRegistry.h>
#include <react/renderer/componentregistry/ComponentDescriptorRegistry.h>
namespace facebook {
namespace react {
class MainComponentsRegistry
    : public facebook::jni::HybridClass<MainComponentsRegistry> {
 public:
  // Adapt it to the package you used for your Java class.
  constexpr static auto kJavaDescriptor =
      "Lcom/rndiffapp/newarchitecture/components/MainComponentsRegistry;";
  static void registerNatives();
  MainComponentsRegistry(ComponentFactory *delegate);
 private:
  static std::shared_ptr<ComponentDescriptorProviderRegistry const>
  sharedProviderRegistry();
  static jni::local_ref<jhybriddata> initHybrid(
      jni::alias_ref<jclass>,
      ComponentFactory *delegate);
};
} // namespace react
} // namespace facebook
android/app/src/main/jni/OnLoad.cpp ADDED1 hidden comment
#include <fbjni/fbjni.h>
#include "MainApplicationTurboModuleManagerDelegate.h"
#include "MainComponentsRegistry.h"
JNIEXPORT jint JNICALL JNI_OnLoad(JavaVM *vm, void *) {
  return facebook::jni::initialize(vm, [] {
    facebook::react::MainApplicationTurboModuleManagerDelegate::
        registerNatives();
    facebook::react::MainComponentsRegistry::registerNatives();
  });
}
android/app/src/main/res/drawable/rn_edit_text_material.xml ADDED0 hidden comment
<?xml version="1.0" encoding="utf-8"?>
<!-- Copyright (C) 2014 The Android Open Source Project
     Licensed under the Apache License, Version 2.0 (the "License");
     you may not use this file except in compliance with the License.
     You may obtain a copy of the License at
          http://www.apache.org/licenses/LICENSE-2.0
     Unless required by applicable law or agreed to in writing, software
     distributed under the License is distributed on an "AS IS" BASIS,
     WITHOUT WARRANTIES OR CONDITIONS OF ANY KIND, either express or implied.
     See the License for the specific language governing permissions and
     limitations under the License.
-->
<inset xmlns:android="http://schemas.android.com/apk/res/android"
       android:insetLeft="@dimen/abc_edit_text_inset_horizontal_material"
       android:insetRight="@dimen/abc_edit_text_inset_horizontal_material"
       android:insetTop="@dimen/abc_edit_text_inset_top_material"
       android:insetBottom="@dimen/abc_edit_text_inset_bottom_material">
    <selector>
        <!-- 
          This file is a copy of abc_edit_text_material (https://bit.ly/3k8fX7I).
          The item below with state_pressed="false" and state_focused="false" causes a NullPointerException.
          NullPointerException:tempt to invoke virtual method 'android.graphics.drawable.Drawable android.graphics.drawable.Drawable$ConstantState.newDrawable(android.content.res.Resources)'
          <item android:state_pressed="false" android:state_focused="false" android:drawable="@drawable/abc_textfield_default_mtrl_alpha"/>
          For more info, see https://bit.ly/3CdLStv (react-native/pull/29452) and https://bit.ly/3nxOMoR.
        -->
        <item android:state_enabled="false" android:drawable="@drawable/abc_textfield_default_mtrl_alpha"/>
        <item android:drawable="@drawable/abc_textfield_activated_mtrl_alpha"/>
    </selector>
</inset>
android/app/src/main/res/values/styles.xml MODIFIED0 hidden comment
    <!-- Base application theme. -->
    <style name="AppTheme" parent="Theme.AppCompat.DayNight.NoActionBar">
        <!-- Customize your theme here. -->
        <item name="android:textColor">#000000</item>
        <item name="android:editTextBackground">@drawable/rn_edit_text_material</item>
    </style>
</resources>
android/build.gradle MODIFIED0 hidden comment
import org.apache.tools.ant.taskdefs.condition.Os
// Top-level build file where you can add configuration options common to all sub-projects/modules.
buildscript {
    ext {
        buildToolsVersion = "29.0.3"
        buildToolsVersion = "31.0.0"
        minSdkVersion = 21
        compileSdkVersion = 29
        targetSdkVersion = 29
        ndkVersion = "20.1.5948944"
        compileSdkVersion = 31
        targetSdkVersion = 31
        if (System.properties['os.arch'] == "aarch64") {
            // For M1 Users we need to use the NDK 24 which added support for aarch64
            ndkVersion = "24.0.8215888"
        } else if (Os.isFamily(Os.FAMILY_WINDOWS)) {
            // For Android Users, we need to use NDK 23, otherwise the build will
            // fail due to paths longer than the OS limit
            ndkVersion = "23.1.7779620"
        } else {
            // Otherwise we default to the side-by-side NDK version from AGP.
            ndkVersion = "21.4.7075529"
        }
    }
    repositories {
        google()
        jcenter()
        mavenCentral()
    }
    dependencies {
        classpath("com.android.tools.build:gradle:4.1.0")
        classpath("com.android.tools.build:gradle:7.0.4")
        classpath("com.facebook.react:react-native-gradle-plugin")
        classpath("de.undercouch:gradle-download-task:4.1.2")
        // NOTE: Do not place your application dependencies here; they belong
        // in the individual module build.gradle files
    }
allprojects {
    repositories {
        mavenLocal()
        maven {
            // All of React Native (JS, Obj-C sources, Android binaries) is installed from npm
            url("$rootDir/../node_modules/react-native/android")
            // Android JSC is installed from npm
            url("$rootDir/../node_modules/jsc-android/dist")
        }
        mavenCentral {
            // We don't want to fetch react-native from Maven Central as there are
            // older versions over there.
            content {
                excludeGroup "com.facebook.react"
            }
        }
        google()
        jcenter()
        maven { url 'https://www.jitpack.io' }
    }
}
android/gradle.properties MODIFIED0 hidden comment
# Specifies the JVM arguments used for the daemon process.
# The setting is particularly useful for tweaking memory settings.
# Default value: -Xmx10248m -XX:MaxPermSize=256m
# org.gradle.jvmargs=-Xmx2048m -XX:MaxPermSize=512m -XX:+HeapDumpOnOutOfMemoryError -Dfile.encoding=UTF-8
# Default value: -Xmx512m -XX:MaxMetaspaceSize=256m
org.gradle.jvmargs=-Xmx2048m -XX:MaxMetaspaceSize=512m
# When configured, Gradle will run in incubating parallel mode.
# This option should only be used with decoupled projects. More details, visit
android.enableJetifier=true
# Version of flipper SDK to use with React Native
FLIPPER_VERSION=0.75.1
FLIPPER_VERSION=0.125.0
# Use this property to specify which architecture you want to build.
# You can also override it from the CLI using
# ./gradlew <task> -PreactNativeArchitectures=x86_64
reactNativeArchitectures=armeabi-v7a,arm64-v8a,x86,x86_64
# Use this property to enable support to the new architecture.
# This will allow you to use TurboModules and the Fabric render in
# your application. You should enable this flag either if you want
# to write custom TurboModules/Fabric components OR use libraries that
# are providing them.
newArchEnabled=false
android/gradle/wrapper/gradle-wrapper.jar MODIFIEDBINARY0 hidden comment
android/gradle/wrapper/gradle-wrapper.properties MODIFIED0 hidden comment
distributionBase=GRADLE_USER_HOME
distributionPath=wrapper/dists
distributionUrl=https\://services.gradle.org/distributions/gradle-6.7-all.zip
distributionUrl=https\://services.gradle.org/distributions/gradle-7.3.3-all.zip
zipStoreBase=GRADLE_USER_HOME
zipStorePath=wrapper/dists
android/gradlew MODIFIED0 hidden comment
#!/usr/bin/env sh
#!/bin/sh
#
# Copyright 2015 the original author or authors.
# Copyright © 2015-2021 the original authors.
#
# Licensed under the Apache License, Version 2.0 (the "License");
# you may not use this file except in compliance with the License.
#
##############################################################################
##
##  Gradle start up script for UN*X
##
#
#   Gradle start up script for POSIX generated by Gradle.
#
#   Important for running:
#
#   (1) You need a POSIX-compliant shell to run this script. If your /bin/sh is
#       noncompliant, but you have some other compliant shell such as ksh or
#       bash, then to run this script, type that shell name before the whole
#       command line, like:
#
#           ksh Gradle
#
#       Busybox and similar reduced shells will NOT work, because this script
#       requires all of these POSIX shell features:
#         * functions;
#         * expansions «$var», «${var}», «${var:-default}», «${var+SET}»,
#           «${var#prefix}», «${var%suffix}», and «$( cmd )»;
#         * compound commands having a testable exit status, especially «case»;
#         * various built-in commands including «command», «set», and «ulimit».
#
#   Important for patching:
#
#   (2) This script targets any POSIX shell, so it avoids extensions provided
#       by Bash, Ksh, etc; in particular arrays are avoided.
#
#       The "traditional" practice of packing multiple parameters into a
#       space-separated string is a well documented source of bugs and security
#       problems, so this is (mostly) avoided, by progressively accumulating
#       options in "$@", and eventually passing that to Java.
#
#       Where the inherited environment variables (DEFAULT_JVM_OPTS, JAVA_OPTS,
#       and GRADLE_OPTS) rely on word-splitting, this is performed explicitly;
#       see the in-line comments for details.
#
#       There are tweaks for specific operating systems such as AIX, CygWin,
#       Darwin, MinGW, and NonStop.
#
#   (3) This script is generated from the Groovy template
#       https://github.com/gradle/gradle/blob/master/subprojects/plugins/src/main/resources/org/gradle/api/internal/plugins/unixStartScript.txt
#       within the Gradle project.
#
#       You can find Gradle at https://github.com/gradle/gradle/.
#
##############################################################################
# Attempt to set APP_HOME
# Resolve links: $0 may be a link
PRG="$0"
# Need this for relative symlinks.
while [ -h "$PRG" ] ; do
    ls=`ls -ld "$PRG"`
    link=`expr "$ls" : '.*-> \(.*\)$'`
    if expr "$link" : '/.*' > /dev/null; then
        PRG="$link"
    else
        PRG=`dirname "$PRG"`"/$link"
    fi
app_path=$0
# Need this for daisy-chained symlinks.
while
    APP_HOME=${app_path%"${app_path##*/}"}  # leaves a trailing /; empty if no leading path
    [ -h "$app_path" ]
do
    ls=$( ls -ld "$app_path" )
    link=${ls#*' -> '}
    case $link in             #(
      /*)   app_path=$link ;; #(
      *)    app_path=$APP_HOME$link ;;
    esac
done
SAVED="`pwd`"
cd "`dirname \"$PRG\"`/" >/dev/null
APP_HOME="`pwd -P`"
cd "$SAVED" >/dev/null
APP_HOME=$( cd "${APP_HOME:-./}" && pwd -P ) || exit
APP_NAME="Gradle"
APP_BASE_NAME=`basename "$0"`
APP_BASE_NAME=${0##*/}
# Add default JVM options here. You can also use JAVA_OPTS and GRADLE_OPTS to pass JVM options to this script.
DEFAULT_JVM_OPTS='"-Xmx64m" "-Xms64m"'
# Use the maximum available, or set MAX_FD != -1 to use that value.
MAX_FD="maximum"
MAX_FD=maximum
warn () {
    echo "$*"
}
} >&2
die () {
    echo
    echo "$*"
    echo
    exit 1
}
} >&2
# OS specific support (must be 'true' or 'false').
cygwin=false
msys=false
darwin=false
nonstop=false
case "`uname`" in
  CYGWIN* )
    cygwin=true
    ;;
  Darwin* )
    darwin=true
    ;;
  MINGW* )
    msys=true
    ;;
  NONSTOP* )
    nonstop=true
    ;;
case "$( uname )" in                #(
  CYGWIN* )         cygwin=true  ;; #(
  Darwin* )         darwin=true  ;; #(
  MSYS* | MINGW* )  msys=true    ;; #(
  NONSTOP* )        nonstop=true ;;
esac
CLASSPATH=$APP_HOME/gradle/wrapper/gradle-wrapper.jar
if [ -n "$JAVA_HOME" ] ; then
    if [ -x "$JAVA_HOME/jre/sh/java" ] ; then
        # IBM's JDK on AIX uses strange locations for the executables
        JAVACMD="$JAVA_HOME/jre/sh/java"
        JAVACMD=$JAVA_HOME/jre/sh/java
    else
        JAVACMD="$JAVA_HOME/bin/java"
        JAVACMD=$JAVA_HOME/bin/java
    fi
    if [ ! -x "$JAVACMD" ] ; then
        die "ERROR: JAVA_HOME is set to an invalid directory: $JAVA_HOME
location of your Java installation."
    fi
else
    JAVACMD="java"
    JAVACMD=java
    which java >/dev/null 2>&1 || die "ERROR: JAVA_HOME is not set and no 'java' command could be found in your PATH.
Please set the JAVA_HOME variable in your environment to match the
fi
# Increase the maximum file descriptors if we can.
if [ "$cygwin" = "false" -a "$darwin" = "false" -a "$nonstop" = "false" ] ; then
    MAX_FD_LIMIT=`ulimit -H -n`
    if [ $? -eq 0 ] ; then
        if [ "$MAX_FD" = "maximum" -o "$MAX_FD" = "max" ] ; then
            MAX_FD="$MAX_FD_LIMIT"
        fi
        ulimit -n $MAX_FD
        if [ $? -ne 0 ] ; then
            warn "Could not set maximum file descriptor limit: $MAX_FD"
        fi
    else
        warn "Could not query maximum file descriptor limit: $MAX_FD_LIMIT"
    fi
if ! "$cygwin" && ! "$darwin" && ! "$nonstop" ; then
    case $MAX_FD in #(
      max*)
        MAX_FD=$( ulimit -H -n ) ||
            warn "Could not query maximum file descriptor limit"
    esac
    case $MAX_FD in  #(
      '' | soft) :;; #(
      *)
        ulimit -n "$MAX_FD" ||
            warn "Could not set maximum file descriptor limit to $MAX_FD"
    esac
fi
# For Darwin, add options to specify how the application appears in the dock
if $darwin; then
    GRADLE_OPTS="$GRADLE_OPTS \"-Xdock:name=$APP_NAME\" \"-Xdock:icon=$APP_HOME/media/gradle.icns\""
fi
# Collect all arguments for the java command, stacking in reverse order:
#   * args from the command line
#   * the main class name
#   * -classpath
#   * -D...appname settings
#   * --module-path (only if needed)
#   * DEFAULT_JVM_OPTS, JAVA_OPTS, and GRADLE_OPTS environment variables.
# For Cygwin or MSYS, switch paths to Windows format before running java
if [ "$cygwin" = "true" -o "$msys" = "true" ] ; then
    APP_HOME=`cygpath --path --mixed "$APP_HOME"`
    CLASSPATH=`cygpath --path --mixed "$CLASSPATH"`
    JAVACMD=`cygpath --unix "$JAVACMD"`
    # We build the pattern for arguments to be converted via cygpath
    ROOTDIRSRAW=`find -L / -maxdepth 1 -mindepth 1 -type d 2>/dev/null`
    SEP=""
    for dir in $ROOTDIRSRAW ; do
        ROOTDIRS="$ROOTDIRS$SEP$dir"
        SEP="|"
    done
    OURCYGPATTERN="(^($ROOTDIRS))"
    # Add a user-defined pattern to the cygpath arguments
    if [ "$GRADLE_CYGPATTERN" != "" ] ; then
        OURCYGPATTERN="$OURCYGPATTERN|($GRADLE_CYGPATTERN)"
    fi
if "$cygwin" || "$msys" ; then
    APP_HOME=$( cygpath --path --mixed "$APP_HOME" )
    CLASSPATH=$( cygpath --path --mixed "$CLASSPATH" )
    JAVACMD=$( cygpath --unix "$JAVACMD" )
    # Now convert the arguments - kludge to limit ourselves to /bin/sh
    i=0
    for arg in "$@" ; do
        CHECK=`echo "$arg"|egrep -c "$OURCYGPATTERN" -`
        CHECK2=`echo "$arg"|egrep -c "^-"`                                 ### Determine if an option
        if [ $CHECK -ne 0 ] && [ $CHECK2 -eq 0 ] ; then                    ### Added a condition
            eval `echo args$i`=`cygpath --path --ignore --mixed "$arg"`
        else
            eval `echo args$i`="\"$arg\""
    for arg do
        if
            case $arg in                                #(
              -*)   false ;;                            # don't mess with options #(
              /?*)  t=${arg#/} t=/${t%%/*}              # looks like a POSIX filepath
                    [ -e "$t" ] ;;                      #(
              *)    false ;;
            esac
        then
            arg=$( cygpath --path --ignore --mixed "$arg" )
        fi
        i=`expr $i + 1`
        # Roll the args list around exactly as many times as the number of
        # args, so each arg winds up back in the position where it started, but
        # possibly modified.
        #
        # NB: a `for` loop captures its iteration list before it begins, so
        # changing the positional parameters here affects neither the number of
        # iterations, nor the values presented in `arg`.
        shift                   # remove old arg
        set -- "$@" "$arg"      # push replacement arg
    done
    case $i in
        0) set -- ;;
        1) set -- "$args0" ;;
        2) set -- "$args0" "$args1" ;;
        3) set -- "$args0" "$args1" "$args2" ;;
        4) set -- "$args0" "$args1" "$args2" "$args3" ;;
        5) set -- "$args0" "$args1" "$args2" "$args3" "$args4" ;;
        6) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" ;;
        7) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" ;;
        8) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" "$args7" ;;
        9) set -- "$args0" "$args1" "$args2" "$args3" "$args4" "$args5" "$args6" "$args7" "$args8" ;;
    esac
fi
# Escape application args
save () {
    for i do printf %s\\n "$i" | sed "s/'/'\\\\''/g;1s/^/'/;\$s/\$/' \\\\/" ; done
    echo " "
}
APP_ARGS=`save "$@"`
# Collect all arguments for the java command;
#   * $DEFAULT_JVM_OPTS, $JAVA_OPTS, and $GRADLE_OPTS can contain fragments of
#     shell script including quotes and variable substitutions, so put them in
#     double quotes to make sure that they get re-expanded; and
#   * put everything else in single quotes, so that it's not re-expanded.
set -- \
        "-Dorg.gradle.appname=$APP_BASE_NAME" \
        -classpath "$CLASSPATH" \
        org.gradle.wrapper.GradleWrapperMain \
        "$@"
# Use "xargs" to parse quoted args.
#
# With -n1 it outputs one arg per line, with the quotes and backslashes removed.
#
# In Bash we could simply go:
#
#   readarray ARGS < <( xargs -n1 <<<"$var" ) &&
#   set -- "${ARGS[@]}" "$@"
#
# but POSIX shell has neither arrays nor command substitution, so instead we
# post-process each arg (as a line of input to sed) to backslash-escape any
# character that might be a shell metacharacter, then use eval to reverse
# that process (while maintaining the separation between arguments), and wrap
# the whole thing up as a single "set" statement.
#
# This will of course break if any of these variables contains a newline or
# an unmatched quote.
#
# Collect all arguments for the java command, following the shell quoting and substitution rules
eval set -- $DEFAULT_JVM_OPTS $JAVA_OPTS $GRADLE_OPTS "\"-Dorg.gradle.appname=$APP_BASE_NAME\"" -classpath "\"$CLASSPATH\"" org.gradle.wrapper.GradleWrapperMain "$APP_ARGS"
eval "set -- $(
        printf '%s\n' "$DEFAULT_JVM_OPTS $JAVA_OPTS $GRADLE_OPTS" |
        xargs -n1 |
        sed ' s~[^-[:alnum:]+,./:=@_]~\\&~g; ' |
        tr '\n' ' '
    )" '"$@"'
exec "$JAVACMD" "$@"
android/settings.gradle MODIFIED0 hidden comment
rootProject.name = 'RnDiffApp'
apply from: file("../node_modules/@react-native-community/cli-platform-android/native_modules.gradle"); applyNativeModulesSettingsGradle(settings)
include ':app'
includeBuild('../node_modules/react-native-gradle-plugin')
if (settings.hasProperty("newArchEnabled") && settings.newArchEnabled == "true") {
    include(":ReactAndroid")
    project(":ReactAndroid").projectDir = file('../node_modules/react-native/ReactAndroid')
}
ios/Podfile MODIFIED0 hidden comment
require_relative '../node_modules/react-native/scripts/react_native_pods'
require_relative '../node_modules/@react-native-community/cli-platform-ios/native_modules'
platform :ios, '10.0'
platform :ios, '11.0'
install! 'cocoapods', :deterministic_uuids => false
target 'RnDiffApp' do
  config = use_native_modules!
  # Flags change depending on the env values.
  flags = get_default_flags()
  use_react_native!(
    :path => config[:reactNativePath],
    # to enable hermes on iOS, change `false` to `true` and then install pods
    :hermes_enabled => false
    :hermes_enabled => flags[:hermes_enabled],
    :fabric_enabled => flags[:fabric_enabled],
    # An absolute path to your application root.
    :app_path => "#{Pod::Config.instance.installation_root}/.."
  )
  target 'RnDiffAppTests' do
  post_install do |installer|
    react_native_post_install(installer)
    __apply_Xcode_12_5_M1_post_install_workaround(installer)
  end
end
end
ios/RnDiffApp.xcodeproj/project.pbxproj MODIFIED0 hidden comment
ios/RnDiffApp/AppDelegate.m DELETED0 hidden comment
ios/RnDiffApp/AppDelegate.mm ADDED1 hidden comment
#import "AppDelegate.h"
#import <React/RCTBridge.h>
#import <React/RCTBundleURLProvider.h>
#import <React/RCTRootView.h>
#import <React/RCTAppSetupUtils.h>
#if RCT_NEW_ARCH_ENABLED
#import <React/CoreModulesPlugins.h>
#import <React/RCTCxxBridgeDelegate.h>
#import <React/RCTFabricSurfaceHostingProxyRootView.h>
#import <React/RCTSurfacePresenter.h>
#import <React/RCTSurfacePresenterBridgeAdapter.h>
#import <ReactCommon/RCTTurboModuleManager.h>
#import <react/config/ReactNativeConfig.h>
@interface AppDelegate () <RCTCxxBridgeDelegate, RCTTurboModuleManagerDelegate> {
  RCTTurboModuleManager *_turboModuleManager;
  RCTSurfacePresenterBridgeAdapter *_bridgeAdapter;
  std::shared_ptr<const facebook::react::ReactNativeConfig> _reactNativeConfig;
  facebook::react::ContextContainer::Shared _contextContainer;
}
@end
#endif
@implementation AppDelegate
- (BOOL)application:(UIApplication *)application didFinishLaunchingWithOptions:(NSDictionary *)launchOptions
{
  RCTAppSetupPrepareApp(application);
  RCTBridge *bridge = [[RCTBridge alloc] initWithDelegate:self launchOptions:launchOptions];
#if RCT_NEW_ARCH_ENABLED
  _contextContainer = std::make_shared<facebook::react::ContextContainer const>();
  _reactNativeConfig = std::make_shared<facebook::react::EmptyReactNativeConfig const>();
  _contextContainer->insert("ReactNativeConfig", _reactNativeConfig);
  _bridgeAdapter = [[RCTSurfacePresenterBridgeAdapter alloc] initWithBridge:bridge contextContainer:_contextContainer];
  bridge.surfacePresenter = _bridgeAdapter.surfacePresenter;
#endif
  UIView *rootView = RCTAppSetupDefaultRootView(bridge, @"RnDiffApp", nil);
  if (@available(iOS 13.0, *)) {
    rootView.backgroundColor = [UIColor systemBackgroundColor];
  } else {
    rootView.backgroundColor = [UIColor whiteColor];
  }
  self.window = [[UIWindow alloc] initWithFrame:[UIScreen mainScreen].bounds];
  UIViewController *rootViewController = [UIViewController new];
  rootViewController.view = rootView;
  self.window.rootViewController = rootViewController;
  [self.window makeKeyAndVisible];
  return YES;
}
- (NSURL *)sourceURLForBridge:(RCTBridge *)bridge
{
#if DEBUG
  return [[RCTBundleURLProvider sharedSettings] jsBundleURLForBundleRoot:@"index"];
#else
  return [[NSBundle mainBundle] URLForResource:@"main" withExtension:@"jsbundle"];
#endif
}
#if RCT_NEW_ARCH_ENABLED
#pragma mark - RCTCxxBridgeDelegate
- (std::unique_ptr<facebook::react::JSExecutorFactory>)jsExecutorFactoryForBridge:(RCTBridge *)bridge
{
  _turboModuleManager = [[RCTTurboModuleManager alloc] initWithBridge:bridge
                                                             delegate:self
                                                            jsInvoker:bridge.jsCallInvoker];
  return RCTAppSetupDefaultJsExecutorFactory(bridge, _turboModuleManager);
}
#pragma mark RCTTurboModuleManagerDelegate
- (Class)getModuleClassFromName:(const char *)name
{
  return RCTCoreModulesClassProvider(name);
}
- (std::shared_ptr<facebook::react::TurboModule>)getTurboModule:(const std::string &)name
                                                      jsInvoker:(std::shared_ptr<facebook::react::CallInvoker>)jsInvoker
{
  return nullptr;
}
- (std::shared_ptr<facebook::react::TurboModule>)getTurboModule:(const std::string &)name
                                                     initParams:
                                                         (const facebook::react::ObjCTurboModule::InitParams &)params
{
  return nullptr;
}
- (id<RCTTurboModule>)getModuleInstanceFromClass:(Class)moduleClass
{
  return RCTAppSetupDefaultModuleFromClass(moduleClass);
}
#endif
@end
ios/RnDiffApp/Images.xcassets/AppIcon.appiconset/Contents.json MODIFIED0 hidden comment
  "images" : [
    {
      "idiom" : "iphone",
      "size" : "29x29",
      "scale" : "2x"
      "scale" : "2x",
      "size" : "20x20"
    },
    {
      "idiom" : "iphone",
      "size" : "29x29",
      "scale" : "3x"
      "scale" : "3x",
      "size" : "20x20"
    },
    {
      "idiom" : "iphone",
      "size" : "40x40",
      "scale" : "2x"
      "scale" : "2x",
      "size" : "29x29"
    },
    {
      "idiom" : "iphone",
      "size" : "40x40",
      "scale" : "3x"
      "scale" : "3x",
      "size" : "29x29"
    },
    {
      "idiom" : "iphone",
      "size" : "60x60",
      "scale" : "2x"
      "scale" : "2x",
      "size" : "40x40"
    },
    {
      "idiom" : "iphone",
      "size" : "60x60",
      "scale" : "3x"
      "scale" : "3x",
      "size" : "40x40"
    },
    {
      "idiom" : "iphone",
      "scale" : "2x",
      "size" : "60x60"
    },
    {
      "idiom" : "iphone",
      "scale" : "3x",
      "size" : "60x60"
    },
    {
      "idiom" : "ios-marketing",
      "scale" : "1x",
      "size" : "1024x1024"
    }
  ],
  "info" : {
    "version" : 1,
    "author" : "xcode"
    "author" : "xcode",
    "version" : 1
  }
}
}
ios/RnDiffApp/main.m MODIFIED0 hidden comment
#import "AppDelegate.h"
int main(int argc, char * argv[]) {
int main(int argc, char *argv[])
{
  @autoreleasepool {
    return UIApplicationMain(argc, argv, nil, NSStringFromClass([AppDelegate class]));
  }
ios/RnDiffAppTests/RnDiffAppTests.m MODIFIED0 hidden comment
@implementation RnDiffAppTests
- (BOOL)findSubviewInView:(UIView *)view matching:(BOOL(^)(UIView *view))test
- (BOOL)findSubviewInView:(UIView *)view matching:(BOOL (^)(UIView *view))test
{
  if (test(view)) {
    return YES;
  __block NSString *redboxError = nil;
#ifdef DEBUG
  RCTSetLogFunction(^(RCTLogLevel level, RCTLogSource source, NSString *fileName, NSNumber *lineNumber, NSString *message) {
    if (level >= RCTLogLevelError) {
      redboxError = message;
    }
  });
  RCTSetLogFunction(
      ^(RCTLogLevel level, RCTLogSource source, NSString *fileName, NSNumber *lineNumber, NSString *message) {
        if (level >= RCTLogLevelError) {
          redboxError = message;
        }
      });
#endif
  while ([date timeIntervalSinceNow] > 0 && !foundElement && !redboxError) {
    [[NSRunLoop mainRunLoop] runMode:NSDefaultRunLoopMode beforeDate:[NSDate dateWithTimeIntervalSinceNow:0.1]];
    [[NSRunLoop mainRunLoop] runMode:NSRunLoopCommonModes beforeDate:[NSDate dateWithTimeIntervalSinceNow:0.1]];
    foundElement = [self findSubviewInView:vc.view matching:^BOOL(UIView *view) {
      if ([view.accessibilityLabel isEqualToString:TEXT_TO_LOOK_FOR]) {
        return YES;
      }
      return NO;
    }];
    foundElement = [self findSubviewInView:vc.view
                                  matching:^BOOL(UIView *view) {
                                    if ([view.accessibilityLabel isEqualToString:TEXT_TO_LOOK_FOR]) {
                                      return YES;
                                    }
                                    return NO;
                                  }];
  }
#ifdef DEBUG
  XCTAssertTrue(foundElement, @"Couldn't find element with text '%@' in %d seconds", TEXT_TO_LOOK_FOR, TIMEOUT_SECONDS);
}
@end
1 /42
