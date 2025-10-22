# Lab-Activity---2 Sample Code
import * as React from 'react';
import { Text, View, StyleSheet } from 'react-native';

export default function App() {
  return (
    <View style={styles.container}>
      <Text style={styles.text}>Hello, Expo Snack!</Text>
    </View>
  );
}

const styles = StyleSheet.create({
  container: {
    flex: 1,
    justifyContent: 'center',
    alignItems: 'center',
    backgroundColor: '#D6EAF8',
  },
  text: {
    fontSize: 24,
    fontWeight: 'bold',
    color: '#2E86C1',
  },
});
