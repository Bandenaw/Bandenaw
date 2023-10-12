  // Android is more verbose, we need to enabled it when we are on an emulator
  // This is a verbose and complex procedure. Please check this method to see what happens
  await AndroidSettings.enableBiometricLogin();
  return prepareBiometrics();
}
