package com.test02;

public class Account {

	private String account;
	private int balance;
	private double interestRate;

	Account() {
	}

	Account(String account, int balance, double interestRate) {
		this.account = account;
		this.balance = balance;
		this.interestRate = interestRate * 0.01;
	}

	public String getAccount() {
		return account;
	}

	public void setAccount(String account) {
		this.account = account;
	}

	public int getBalance() {
		return balance;
	}

	public double calculateInterest() {
		return this.balance * interestRate;
	}

	public void deposit(int money) {
		this.balance += money;
	}

	public void withdraw(int money) {
		this.balance -= money;
	}

}
