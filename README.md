# Bujji-chata// BujjiChat – Romantic WhatsApp-style App (Version 1 UI)

import React from "react";
import { Card, CardContent } from "@/components/ui/card";
import { Input } from "@/components/ui/input";
import { Button } from "@/components/ui/button";
import { motion } from "framer-motion";
import { Heart } from "lucide-react";

export default function BujjiChat() {
  return (
    <div className="min-h-screen bg-pink-50 flex flex-col items-center justify-center p-4">
      <motion.h1
        className="text-3xl font-bold mb-6 text-pink-700"
        initial={{ opacity: 0, y: -20 }}
        animate={{ opacity: 1, y: 0 }}
        transition={{ duration: 0.6 }}
      >
        💖 BujjiChat
      </motion.h1>

      <
